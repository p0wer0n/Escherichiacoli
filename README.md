PushIRCBouncer
===============

NodeJS IRC push notifications.

Configuration
==================
Edit config.coffee with your favorite text editor
Put in the application ID and secret from the application that you will create later where needed.
Edit the trigger words and channel info 

Setup Instructions
==================
Register an account at https://instapush.im/
Download the iOS or Android app
Sign in to the app
Sign in to the site
Go to the dashboard
Add an application
Create an event for that application
Call it "mention"
For the tracker, put in channel, press tab, username, press tab, and message, and press tab.
For the message, format it to your preference.
Example:
({channel}) <{username}>: "{message}"
A message sent by TestUser in the channel #testchannel that says "test message" would show up as (#testchannel) <TestUser>: "test message" on your phone

