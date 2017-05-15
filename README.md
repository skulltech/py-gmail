# py-gmail
A simple Python script for sending email from your Gmail account

### Installation

1. Download the `client_secret.json` for your app from Google API console and place it in the same folder as of this script.
2. Install the requirements by running `pip install -r requirements.txt`.

### Usage Instructions

```
import pygmail
response = pygmail.send_mail('sender@gmail.com', 'receiver@email.com', 'Message Subject', 'Message text')
```
