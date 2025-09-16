# 📚 Book Store (MERN Stack)

A full-stack **Book Store Management Application** built with the **MERN stack (MongoDB, Express, React, Node.js)**. This project allows users to **create, read, update, and delete (CRUD)** book entries with a clean user interface and a RESTful backend API.

---

## 🚀 Features

* 📖 Add new books with details (title, author, publish year, etc.)
* 📑 View all books in **card view** and **table view**
* ✏️ Edit book details
* 🗑️ Delete books
* ⚡ Real-time UI updates
* 🎨 Styled with **Tailwind CSS** + responsive design

---

## 🛠️ Tech Stack

**Frontend:** React, Vite, Tailwind CSS, Axios
**Backend:** Node.js, Express.js, MongoDB, Mongoose
**Tools:** ESLint, PostCSS, Git, Vite

---

## 📂 File Structure

```
book-store
├── backend/
│   ├── models/
│   │   └── bookModel.js      # Mongoose schema for books
│   ├── routes/
│   │   └── booksRoute.js     # API routes for CRUD operations
│   └── index.js              # Express server setup
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── home/         # Book-related UI components
│   │   │   ├── BackButton.jsx
│   │   │   └── Spinner.jsx
│   │   ├── pages/            # Pages for CRUD (Home, Create, Edit, Show, Delete)
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── public/
│   ├── index.html
│   └── tailwind.config.js
│
├── .env                      # Environment variables
├── README.md                 # Documentation
└── package.json
```

---

## ⚙️ Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/book-store.git
   cd book-store
   ```

2. **Backend Setup:**

   ```bash
   cd backend
   npm install
   npm start
   ```

   * Runs on [http://localhost:5000](http://localhost:5000)

3. **Frontend Setup:**

   ```bash
   cd frontend
   npm install
   npm run dev
   ```

   * Runs on [http://localhost:5173](http://localhost:5173)

---

## 📡 API Endpoints

| Method | Endpoint        | Description         |
| ------ | --------------- | ------------------- |
| GET    | /api/books      | Get all books       |
| GET    | /api/books/\:id | Get a single book   |
| POST   | /api/books      | Add a new book      |
| PUT    | /api/books/\:id | Update book details |
| DELETE | /api/books/\:id | Delete a book       |

---

## 📸 Screenshots

📌 *Add your UI screenshots here for better visualization.*

---

## 🧠 What I Learned

* Full-stack development with **MERN stack**
* RESTful API design with Express.js
* MongoDB schema design and CRUD operations
* React component-based architecture
* State management and API integration with Axios
* Styling and responsiveness with Tailwind CSS

---

## 🛠️ Future Improvements

* 🔐 Add authentication (JWT-based login/signup)
* 🔍 Add search and filter options
* ⭐ Add book ratings and reviews
* ☁️ Deploy on cloud platforms (Render, Vercel, MongoDB Atlas)

---

## 🛡️ License

This project is licensed under the **MIT License** – feel free to use and modify it.

---
