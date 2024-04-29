<h1 align="center"> Chatt App </h1>
This  App is a real-time messaging platform that enables users to communicate seamlessly. Built with React.js for the frontend, Express.js and Node.js for the backend, and MongoDB for the database, this application provides an intuitive and secure environment for users to chat with one another.


## Features
* Real-time Communication: Chat with other users instantly.

* User Authentication: Securely log in and authenticate users.

* Message History: View previous messages.

* Online Status: See who's online.

## Technologies Used
- Frontend (React.js): The frontend is built using React.js, providing a responsive and interactive user interface.

- Backend (Express.js & Node.js): The backend is powered by Express.js and Node.js, handling user authentication, message routing, and database interactions.

- Database (MongoDB): MongoDB is used to store user information, message history, and other data required by the application.

- Websockets (Socket.IO): Socket.IO enables real-time, bidirectional communication between the client and server, ensuring instant message delivery.

## Installation
1. Clone the repository:
```bash
git clone https://github.com/subhra8697/chat-app.git
```

2. Install dependencies:
```bash
cd chat-app
npm install
```

3. Set up environment variables: Create a .env file in the root directory and define the following variables:
```makefile
PORT=3001
MONGODB_URI=your_mongodb_uri
```

4. Start the server:
```bash
npm start
``` 

5. Start the client:
```bash
cd client
npm run dev
```

## Usage
- Visit http://localhost:3000 to access the chat app.
- Sign up or log in to start chatting with other users.

## Contribution
Contributions to the project are welcome! Whether it's fixing bugs, implementing new features, or improving the user experience, feel free to contribute by opening a pull request or submitting an issue.