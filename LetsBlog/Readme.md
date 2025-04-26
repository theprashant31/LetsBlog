# Let's Blog - Node.js Project

Welcome to **Let's Blog**, a simple Node.js blogging platform!

This project allows users to create, read, update, and delete blog posts. It uses **Express.js** for server-side operations, **MongoDB** for database management, and **EJS** for templating views.

---

## 🚀 Features

- Create new blog posts
- View all blog posts
- Edit existing blog posts
- Delete blog posts

---

## 🛠 Tech Stack

- **Node.js**
- **Express.js**
- **MongoDB** with **Mongoose**
- **EJS** Templating Engine
- **Body-Parser** Middleware
- **Method-Override** for supporting PUT/DELETE methods
- **Dotenv** for environment variables

---

## 📥 Installation

1. **Clone the repository:**
```bash
git clone https://github.com/theprashant31/LetsBlog.git
```

2. **Navigate into the project directory:**
```bash
cd LetsBlog
```

3. **Install dependencies:**
```bash
npm install
```

4. **Set up environment variables:**
- Create a `.env` file in the root directory
- Add the following:
```dotenv
PORT=3000
MONGODB_URI=your_mongodb_connection_string
```

5. **Start the application:**
```bash
npm start
```

6. **Visit the app in your browser:**
```
http://localhost:3000/
```

---

## 📂 Folder Structure

```
LetsBlog/
├── models/
│   └── blog.js
├── public/
│   └── (static files like CSS, images)
├── routes/
│   └── index.js
├── views/
│   ├── partials/
│   │   ├── header.ejs
│   │   └── footer.ejs
│   ├── blogs/
│   │   ├── index.ejs
│   │   ├── new.ejs
│   │   ├── show.ejs
│   │   └── edit.ejs
│   └── home.ejs
├── app.js
├── package.json
└── README.md
```

---

## 📜 Scripts

- **Start the server:**
```bash
npm start
```

---

## 📦 Main Dependencies

| Package          | Purpose                              |
| ---------------- | ------------------------------------ |
| express          | Web framework                       |
| mongoose         | MongoDB ORM                          |
| ejs              | Templating engine                    |
| body-parser      | Parse incoming request bodies        |
| method-override  | Support PUT and DELETE from forms    |
| dotenv           | Environment variable management     |

---