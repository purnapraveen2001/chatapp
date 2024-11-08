
Welcome to **Chat App**! This project is a real-time chat application built with React, Node.js, and Socket.IO, providing users with a seamless and interactive messaging experience.

## 🚀 Project Overview

Chat App is a full-stack real-time messaging application that allows users to register, log in, and communicate with others instantly. With a user-friendly interface and a responsive backend, Chat App aims to deliver a smooth and reliable chatting experience.

## ✨ Features

- **User Authentication**: Secure registration and login with JWT-based authentication.
- **Real-time Messaging**: Instantly send and receive messages with Socket.IO.
- **Responsive UI**: Works on both desktop and mobile devices.
- **User Status**: See online/offline statuses of other users.
- **Typing Indicators**: Know when someone is typing in the chat.
- **Message Persistence**: Messages are stored for users to revisit past conversations.

## 🛠️ Technologies Used

- **Frontend**: React, CSS
- **Backend**: Node.js, Express, Socket.IO
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)

## 📷 Screenshots

### Login Page
This is the login page where users can enter their credentials to access the chat app.

![Screenshot 2024-11-08 at 7 01 24 AM](https://github.com/user-attachments/assets/6a8de726-0f41-4627-8f26-85f0b90f8f22)

### Chat Interface
Add more screenshots for other sections of your application (like the chat interface, registration page, etc.) by placing images in the `assets` folder and referencing them in the README as shown above.

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/en/download/) (version 14 or later recommended)
- [MongoDB](https://www.mongodb.com/try/download/community)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/purnapraveen2001/chatapp.git
   cd chatapp
   ```

2. **Backend Setup**:
   - Navigate to the backend folder:
     ```bash
     cd backend
     ```
   - Install backend dependencies:
     ```bash
     npm install
     ```
   - Set up environment variables by creating a `.env` file:
     ```plaintext
     PORT=5000
     MONGO_URI=your_mongo_db_uri
     JWT_SECRET=your_jwt_secret
     ```
   - Start the backend server:
     ```bash
     npm run dev
     ```

3. **Frontend Setup**:
   - Navigate to the frontend folder:
     ```bash
     cd ../frontend
     ```
   - Install frontend dependencies:
     ```bash
     npm install
     ```
   - Start the frontend server:
     ```bash
     npm start
     ```

### Running the Application

1. Ensure both backend and frontend servers are running.
2. Open your browser and visit `http://localhost:3000` to access the Chat App.

## 📁 Project Structure

```
chatapp/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── .env.example
└── frontend/
    ├── public/
    ├── src/
    │   ├── components/
    │   ├── pages/
    │   ├── App.js
    │   └── index.js
    └── package.json
```

## 🤝 Contributing

Contributions are welcome! Feel free to open issues, submit pull requests, or suggest new features.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.


## 📧 Contact

**Purna Praveen Battula**  
Email: [purnapraveen.battula@gwu.edu](mailto:purnapraveen.battula@gwu.edu)

