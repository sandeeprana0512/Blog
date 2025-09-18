# 📝 Blog App (Node.js + Express + EJS)

A simple full-stack blog application using Node.js, Express, EJS, and Axios. It features a RESTful API backend and a frontend server for managing blog posts.

## 📁 Project Structure
```bash
blog/
├── api/                   # API Server (port 4000)
│   └── server.js
├── frontend/              # Frontend Server (port 3000)
│   ├── server.js
│   ├── views/
│   │   ├── index.ejs
│   │   └── modify.ejs
│   └── public/
│       └── styles/
│           └── main.css
├── package.json
```

## 🚀 Features

View all blog posts

Create a new blog post

Edit existing blog posts

Delete posts

Clean UI with responsive styling

## 📦 Dependencies

Express

Body-parser

EJS

Axios

## ⚙️ Setup Instructions
1. Clone the Repository
```bash 
git clone https://github.com/sandeeprana0512/blog.git
cd blog
```

2. Install Dependencies
```bash
npm install
```

Ensure that you run this in both the API and frontend directories if they're in separate folders.

3. Start the API Server
```bash
# From blog/api directory
node server.js
# Runs on http://localhost:4000
```

4. Start the Frontend Server
```bash
# From blog/frontend directory
node server.js
# Runs on http://localhost:3000
```

## 🌐 Usage

Navigate to http://localhost:3000 in your browser.

Click "New Post" to create a blog entry.

Edit or delete posts using the buttons provided.

Posts are stored in-memory (no database), so they reset when the server restarts.

## 🛠 Future Improvements

Add persistent storage with a database (MongoDB, PostgreSQL, etc.)

Form validation

Rich text editor for posts

User authentication

## 📄 License

This project is licensed under the ISC License
.
