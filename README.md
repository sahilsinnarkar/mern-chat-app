# Chat App

A real-time chat application built using the **MERN stack** (MongoDB, Express, React, Node.js) with **Socket.IO** for seamless bi-directional communication. This project enables users to connect, chat, and share in a secure and responsive environment.

## Features

- Real-time messaging with **Socket.IO**
- User authentication (Sign up, Log in, Log out)
- Create and join chat rooms
- Private and group chats
- User profile management
- Media upload support via **Cloudinary**
- Responsive design using **Daisy UI**
- Persistent chat history with **MongoDB Atlas**

## Tech Stack

- **Frontend**: React (with Vite), Daisy UI, JavaScript (JSX)
- **Backend**: Node.js, Express.js, Socket.IO, MongoDB Atlas
- **Other Tools**: Cloudinary, JSON Web Tokens (JWT), bcrypt.js

## Prerequisites

- Node.js
- MongoDB Atlas account
- Cloudinary account

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/chat-app.git
   cd chat-app
2. **Install dependies**
- backend: npm install
- frontend: npm install

3. **Ennviornment variables** (.env)
MONGO_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
JWT_SECRET=your_jwt_secret

4. **Run application**
- production: npm run start
- development: npm run dev

5. **Build Frontend From the root directory:**
npm run build

**Scripts**
npm run build: Installs dependencies for both backend and frontend and builds the frontend.
npm run dev --prefix backend: Starts the backend server in development mode with nodemon.
npm run start: Starts the backend server in production mode.

**Screenshots**
![image](https://github.com/user-attachments/assets/1f114e8b-afd6-4ea5-86ee-c5c11c3331a0)
![image](https://github.com/user-attachments/assets/e28eea5c-6a9d-4c71-938b-33acdafe91b4)
![image](https://github.com/user-attachments/assets/c19e1c9c-338d-419b-a8e7-b3adcdf9b5b4)
![image](https://github.com/user-attachments/assets/c7e45998-9bac-4e15-a8f2-09a0ee359890)



