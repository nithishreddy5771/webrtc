# WebRTC Video Chat Application

A simple WebRTC-based video chat application using Node.js and WebSocket for signaling.

## Features

- Real-time video chat between two users
- WebSocket-based signaling server
- Separate sender and receiver interfaces

## Setup

1. Install dependencies:
```bash
npm install
```

2. Start the server:
```bash
npm start
```

3. Access the application:
- Sender: http://localhost:3000/sender
- Receiver: http://localhost:3000/receiver

## Technical Stack

- Node.js
- WebSocket
- WebRTC
- HTML/JavaScript

## Project Structure

```
├── server.js          # Signaling server
├── sender/
│   └── index.html    # Sender interface
└── receiver/
    └── index.html    # Receiver interface
```


