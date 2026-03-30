# 📝 Blog Application (Full Stack)

A full-stack Blog Application built using **Spring Boot (Backend)** and **React (Frontend)** that allows users to create, read, update, and delete blog posts with authentication and like functionality.

---

## 🚀 Features

### 🔐 Authentication & Authorization

* User Signup & Login using Email & Password
* Secure password storage (hashed passwords)
* Spring Security integration

### 📝 Blog Management

* Create, Update, Delete blog posts
* View all blog posts (feed)
* View individual blog details

### ❤️ Like System

* Like/Unlike blogs
* Track total likes per blog
* Store users who liked a blog

### 🔎 Additional Features

* Pagination & Sorting
* RESTful APIs
* Clean UI using React

---

## 🛠️ Tech Stack

### Backend

* Java
* Spring Boot
* Spring Security
* Hibernate / JPA
* PostgreSQL

### Frontend

* React (Vite)
* HTML, CSS, JavaScript
* Axios (API calls)

---

## 📂 Project Structure

### Backend (Spring Boot)

```
src/main/java/com/blogapp
│── controller
│── service
│── repository
│── entity
│── security
│── dto
```

### Frontend (React)

```
src/
│── components/
│── pages/
│── services/
│── App.jsx
```

---

## ⚙️ Setup Instructions

### 🔹 Backend Setup

1. Clone the repository

```
git clone https://github.com/your-username/blog-app.git
cd backend
```

2. Configure database in `application.properties`

```
spring.datasource.url=jdbc:postgresql://localhost:5432/blogdb
spring.datasource.username=your_username
spring.datasource.password=your_password
```

3. Run the application

```
mvn spring-boot:run
```

---

### 🔹 Frontend Setup

1. Navigate to frontend folder

```
cd frontend
```

2. Install dependencies

```
npm install
```

3. Start the app

```
npm run dev
```

---

## 🔗 API Endpoints (Sample)

### Auth APIs

* `POST /api/auth/signup`
* `POST /api/auth/login`

### Blog APIs

* `GET /api/blogs` → Get all blogs
* `POST /api/blogs` → Create blog
* `PUT /api/blogs/{id}` → Update blog
* `DELETE /api/blogs/{id}` → Delete blog

### Like APIs

* `POST /api/blogs/{id}/like`
* `DELETE /api/blogs/{id}/like`

---

## 📸 Screenshots

*Add screenshots here (Home Page, Login Page, Blog Feed, etc.)*

---

## 📌 Future Enhancements

* Comments on blogs
* Search functionality
* JWT-based authentication
* User profile page

---

## 🤝 Contribution

Contributions are welcome! Feel free to fork the repo and submit a PR.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Rahul Chandra**
Aspiring Software Engineer | Java | Spring Boot | React

---

## ⭐ Show your support

If you like this project, give it a ⭐ on GitHub!
