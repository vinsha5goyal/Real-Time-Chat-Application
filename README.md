# Real-Time-Chat-Application
# 💬 Real-Time Chat Application

A full-stack real-time chat application built using the MERN Stack and Socket.IO. The application enables users to communicate instantly with real-time message delivery, user authentication, online user status tracking, and media sharing capabilities.

## 🚀 Features

* 🔐 User Authentication & Authorization
* 👤 User Registration and Login
* 💬 Real-Time One-to-One Messaging
* 🟢 Online/Offline User Status
* ⚡ Instant Message Delivery using Socket.IO
* 📷 Image Sharing with Cloudinary
* 🎨 Responsive and Modern UI
* 🔄 Redux Toolkit State Management
* 🌐 REST API Integration
* 📱 Mobile-Friendly Design

## 🛠️ Tech Stack

### Frontend

* React.js
* Redux Toolkit
* Tailwind CSS
* Axios
* Socket.IO Client

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* Socket.IO
* JWT Authentication
* Bcrypt.js
* Cloudinary

## 📂 Project Structure

```bash
Real-Time-Chat-Application
│
├── backend
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   └── index.js
│
├── frontend
│   ├── src
│   ├── components
│   ├── pages
│   ├── redux
│   └── App.jsx
│
└── README.md
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/Real-Time-Chat-Application.git
cd Real-Time-Chat-Application
```

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside backend folder:

```env
PORT=5000
MONGODB_URL=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Start Backend Server:

```bash
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## 🔗 Environment Variables

| Variable              | Description           |
| --------------------- | --------------------- |
| MONGODB_URL           | MongoDB Database URL  |
| JWT_SECRET            | Secret Key for JWT    |
| CLOUDINARY_CLOUD_NAME | Cloudinary Cloud Name |
| CLOUDINARY_API_KEY    | Cloudinary API Key    |
| CLOUDINARY_API_SECRET | Cloudinary API Secret |

## 🌍 Deployment

### Frontend

* Vercel
* Netlify

### Backend

* Render
* Railway

### Database

* MongoDB Atlas

## 🔒 Authentication Flow

1. User registers an account.
2. Password is hashed using bcrypt.
3. JWT token is generated after login.
4. Protected routes are accessed using JWT verification.
5. User remains authenticated during the session.

## ⚡ Real-Time Communication

Socket.IO is used to:

* Establish WebSocket connections.
* Track online users.
* Send and receive messages instantly.
* Broadcast updates without page refresh.

## 📈 Future Improvements

* Group Chats
* Voice Messages
* Video Calling
* Message Reactions
* Read Receipts
* Typing Indicators
* Push Notifications

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License.

## 👩‍💻 Author

**Vinsha Goyal**

GitHub: https://github.com/vinsha5goyal

---

⭐ If you like this project, consider giving it a star on GitHub!
