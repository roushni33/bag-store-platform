# 👜 A Premium Bag Shop

A feature-rich, full-stack web application designed for showcasing and selling premium bags online. Built with **Node.js**, **Express**, **MongoDB**, and **EJS**, it offers secure user authentication via **JWT** and **cookies**, with clean server-side rendering for a seamless shopping experience.

---

## 🚀 Features

- 🛍️ Product listing (bags only)
- 🔍 Single product detail view
- 👤 User authentication using JWT
- 🍪 Secure session management via cookies
- 🛡️ Protected routes for user actions
- 🖼️ EJS templating for server-side rendering
- 📦 MongoDB for storing user and product data

---

## 🛠️ Tech Stack

| Technology       | Description                    |
|------------------|--------------------------------|
| **Node.js**      | JavaScript runtime             |
| **Express.js**   | Web application framework      |
| **MongoDB**      | NoSQL database                 |
| **Mongoose**     | ODM for MongoDB                |
| **EJS**          | Server-side templating engine  |
| **JWT**          | Token-based authentication     |
| **Cookies**      | Session management             |
| **HTML/CSS/JS**  | Frontend rendering and styles  |

---



---

## 🔐 Authentication Flow

1. Users sign up or log in.
2. JWT is generated and stored in HTTP-only cookies.
3. Protected routes validate the token for secure access.
4. Logging out clears the cookie and ends the session.

---


