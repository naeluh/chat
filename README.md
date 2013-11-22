# 3d chat

Built with:

  - <strong>Server side:</strong> Node.js, Socket.io, Express, Redis
  - <strong>Client side:</strong> HTML5 Boilerplate, Bootstrap, Handlebars and jQuery

### Requires

  - Node.js
  - NPM (Node Package Manager)
  - Redis

### Run

Fetch dependencies:

    npm install

Launch Redis:
    
    redis-server

Launch chat server:
    
    (don't forget to launch Redis before!)

    node chatServer.js
    
### Broadcast API

Send messages to all connected users:

    Content-Type: application/json
    POST /api/broadcast/

    {"msg": "Hello!"}
