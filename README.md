# 📚 Book Store Frontend

This is the **frontend** of the Book Store Web App, built using **React (Vite)**. It provides a responsive and user-friendly interface for browsing books and handling user authentication.

---

## 🚀 Live Demo

🌐 https://bookstore-frontend-sand.vercel.app/

---

## ✨ Features

* 🔐 User Signup & Login UI
* 📖 Browse Books / Courses
* ⚡ API integration using Axios
* 🎨 Responsive design with Tailwind CSS
* 🔄 Dynamic routing with React Router

---

## 🛠️ Tech Stack

* React (Vite)
* React Router DOM
* Axios
* Tailwind CSS

---

## 📁 Project Structure

```bash
Frontend/
│
├── src/
│   ├── components/
│   │   ├── Freebook.jsx
│   │   ├── Login.jsx
│   │   ├── Logout.jsx
│   │   ├── Navbar.jsx
│   │   └── Signup.jsx
│   │
│   ├── context/
│   ├── courses/
│   ├── Home/
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── .env
├── index.html
├── package.json
├── tailwind.config.js
├── vite.config.js
└── vercel.json
```

---

## ⚙️ Setup & Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/nidhi-kumari10/bookstore-frontend.git
cd bookstore-frontend
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Environment Variables

Create a `.env` file in the root directory:

```env
VITE_API_URL=your_backend_url_here
```

> Replace `your_backend_url_here` with your deployed backend URL (e.g., Render API URL).

---

### 4️⃣ Run Locally

```bash
npm run dev
```

---

## 🔗 API Connection

All API requests use:

```js
const API_URL = import.meta.env.VITE_API_URL;
```

---

## 🚀 Deployment

* Hosted on **Vercel**
* Connected to GitHub repository
* Automatic deployment on every push

---

## 📌 Future Improvements

* 🛒 Add cart functionality
* ⭐ Ratings & reviews system
* 🔍 Search & filtering options

---

## 👨‍💻 Author

**Kumari Nidhi**


