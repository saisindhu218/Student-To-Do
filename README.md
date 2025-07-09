# Student-To-Do
Of course, Sindhu 💚 — here's your **cleaned-up README content in plain text** with no code blocks or highlight boxes. You can copy and paste this directly into your `README.md` file or a Word document.

---

# 📚 Student To-Do List Web App

A simple full-stack to-do list app that helps students manage tasks effectively. Includes login, signup, task creation, viewing, completion, and deletion features.

---

## 🚀 Features

* 🔐 User Sign Up & Login (with password hashing)
* ✅ Add and manage personal tasks
* 📝 View tasks specific to each user
* 🗑️ Mark tasks as complete or delete them
* 🎨 Clean, responsive user interface

---

## 🛠️ Tech Stack

**Frontend:**
HTML5, CSS3, JavaScript (Vanilla)

**Backend:**
Node.js, Express.js, MongoDB (via Mongoose), bcryptjs (for password encryption), cors (for frontend-backend connection)

---

## 📁 Folder Structure

todo-app/
├── backend/
│   ├── server.js
│   └── models/
│       ├── User.js
│       └── Task.js
├── public/
│   ├── index.html       → Add task page
│   ├── tasks.html       → View task page
│   ├── login.html       → Login page
│   ├── signup.html      → Signup page
│   └── style.css        → Styling
└── README.md

---

## 💻 Getting Started

### 1. Prerequisites

Ensure the following are installed on your system:

* Node.js
* MongoDB
* MongoDB Compass (optional)
* Visual Studio Code (recommended)

---

### 2. Installation Steps

* Clone the repository:
  git clone [https://github.com/your-username/student-todo-app.git](https://github.com/your-username/student-todo-app.git)

* Navigate to the backend folder:
  cd student-todo-app/backend

* Initialize Node and install backend dependencies:
  npm install

* Make sure MongoDB is running:
  mongod

---

### 3. Run the Server

To start the server, run:
node server.js

You should see a message like:
“Server started on port 5000”
“Connected to MongoDB”

---

### 4. Run the Frontend

Open `signup.html` or `login.html` from the `public/` folder in your browser.
You can also use the Live Server extension in VS Code for a better experience.

---

## 🌐 API Endpoints

POST   /api/register     → Register a new user
POST   /api/login        → Login user
POST   /api/tasks        → Create new task
GET    /api/tasks/\:username   → Get all tasks for user
PUT    /api/tasks/\:id         → Update task (mark complete)
DELETE /api/tasks/\:id         → Delete task

---

## 📸 Screenshots

(You can add screenshots of login, task list, and UI pages here once uploaded to GitHub or use image links.)

---

## 🧠 Future Improvements

* Add mobile responsiveness
* Set deadlines or reminders for tasks
* Add task categories like Study, Homework, Project
* Add forgot password/reset password feature
* Use JWT-based session handling for better security

---

## 🙋‍♀️ Author

**Rachabattuni Sai Sindhu**
MCA Student @ Jain (Deemed-to-be University), Bangalore
Passionate about full-stack development and real-world project building.

---

## 📄 License

This project is free and open-source for learning and development purposes.

---

Let me know when you upload it to GitHub so I can help add a cover image or badge if you'd like! 💪📦
