# 💬 Chat App

A real-time chat application with room-based functionality built using **Node.js**, **Express**, and **Socket.IO**, with optional **Redis adapter** support for horizontal scaling.

This project demonstrates how to build scalable and interactive chat systems using WebSockets, Redis, and modern JavaScript tooling.

---

##  Features

- 🔸 Join different chat rooms dynamically
- 🔸 Send and receive real-time messages using WebSockets
- 🔸 Automatic user join/leave notifications
- 🔸 See live list of participants in each room
- 🔸 Timestamps added to messages using Moment.js
- 🔸 Scalable Redis-based adapter (optional for clustering)
- 🔸 Responsive UI built with HTML, CSS, and JavaScript

---

##  Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **WebSocket**: Socket.IO
- **Clustering**: Redis + @socket.io/redis-adapter
- **Utils**: dotenv, moment

---


## 📁 Project Structure
chatapp/
├── public/ # Static frontend files
│ ├── css/
│ ├── js/
│ └── chat.html
├── utils/ # Helper functions
│ ├── messages.js
│ └── users.js
├── server.js # Main backend file
├── .env # Environment variables
├── package.json
└── README.md

### Installations
clone the project
install dependencies
npm run dev

The port = 3000

### 📸 Demo
For a live demo video, check out my LinkedIn post




