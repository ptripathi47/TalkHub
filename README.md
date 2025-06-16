# 💬 TalkHub App

**TalkHub** is a full-stack, one-to-one chat application built with the **MERN stack** and **Socket.IO**, providing users with a platform to exchange messages instantly. It integrates **JWT** for secure authentication and ensures persistent message storage with **MongoDB**.

---

## 📌 Project Overview

- **Users** can register, log in securely, and start chatting with other registered users.
- **Real-time communication** powered by WebSockets ensures instant message delivery without page refresh.
- **Chat history** is stored and retrievable for each conversation.

---

## ✨ Features

### 🏠 Public Features

- **User Registration**
  - New users can register by providing their email and password.

- **User Login**
  - Secure login using **JWT-based authentication**.

- **Logout Functionality**
  - Safely end sessions from the frontend.

---

### 💬 Chat Features

After logging in, users can:

- **Send and Receive Messages**
  - Instant message delivery through **Socket.IO** WebSockets.
  
- **View Chat History**
  - Access previously sent and received messages, fetched from **MongoDB**.

- **Persistent Chat Sessions**
  - Messages remain stored even after logout or page reload.

---

## 🛠️ Tech Stack

| Technology  | Usage |
|:-------------|:----------|
| React.js      | Frontend Development |
| Node.js + Express.js | Backend APIs |
| MongoDB       | Database |
| Socket.IO     | Real-time Communication |
| JWT           | Authentication |
| Vercel        | Deployment |

---

## 🚀 Deployment — Vercel

The application is deployed on **Vercel**, ensuring scalable and reliable hosting for both frontend and backend services.

---

## 🚀 Live Demo

🌐 Click this: [https://work-hive-1ack.vercel.app](https://talk-hub-mbz5.vercel.app/)

---

## 📦 Getting Started

To get started with the Real-Time Chat App project, follow these steps:

1. Clone the repository from GitHub:

2. **Set Environment Variables**: Navigate to the `frontend` and `backend` folders and add necessary environment variables. You may need to create a `.env` file and configure it with required variables:
   
   In the backend/.env file:

   ```
   MONGODB_URI = your-mongo-url
   JWT_SECRET = your-jwt-secret
   CLOUDINARY_CLOUD_NAME = Your-cloundinary-name
   CLOUDINARY_API_KEY = your-cloudinary-api-key
   CLOUDINARY_API_SECRET = your-cloudinary-secret-key
   NODE_ENV = 'production'
   ```

   In the frontend/.env file:

   ```
   VITE_BACKEND_URL = your-server-url
   ```

4. **Install Dependencies**: Install dependencies in the `frontend` and `backend` folders using npm or yarn:

   ```
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

5. **Start the Backend Server**: In the `backend` folder, start the development server using npm:

   ```
   npm run server
   ```

6. **Start the Frontend**: In the `frontend` folder, start the frontend application:

   ```
   npm run dev
   ```
