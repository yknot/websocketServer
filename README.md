# websocketServer
websocket server in node to monitor pushbullet commands

# Install

## Dependencies
* node ws
* inotifywait?

## Setup
* clone git repo
* create file for apiKey (shell script?)
* create latestpush file (getdate?)
* run as service?





# Files

## logMonitor.sh
* starts node server to monitor websocket
* starts inotifywait to monitor log file

## pushbulletWebsocket.js
* monitors websocket and logs events

## runCommands.py
* parses new pushes and executes commands

## py_modules\PushBullet.py
* API caller

## py_modules\Pantry.py
* interact with pantry dictionary

