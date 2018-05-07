# ProjectRTC

## WebRTC Live Streaming

- Node.js server
- Desktop client
- [Android client](https://github.com/pchab/AndroidRTC)

You can also check this iOS client from Digix Technology:

- [iOS client](https://github.com/digixtechnology/iOSRTC)

The signaling part is done with [socket.io](socket.io).
The client is built with [angularjs](https://angularjs.org/).

## Install

It requires [node.js](http://nodejs.org/download/)

* cd ProjectRTC/
* npm install

## run

* Config ICE Services in rtcClient.js

        Modify:
        ```
        iceServers: [
                    {"url": "stun:23.21.150.121"},
                    {"url": "stun:stun.l.google.com:19302"}
                  ]
        ```

* node app

The server will run on port 3000.
You can test it in the (Chrome or Firefox) browser at localhost:3000.
