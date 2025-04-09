# 🚀 Full Stack Developer Test - viAct Clone

This project is a full-stack clone of [dev.viact.net](https://dev.viact.net), providing user authentication via **email/password** and **Google Login**.

## 📁 Project Structure
    .
    ├── viact-frontend/                 # Frontend: React + Material UI + Vite + TypeScript 
    ├── viact-auth/                     # Backend: NestJS + MySQL + TypeORM + JWT 
    ├── docker-compose.yml
    └── README.md

## 📌 GitHub Links
**FE: [https://github.com/minhducn14/viact-frontend.git](https://github.com/minhducn14/viact-frontend.git)
**
**BE: [https://github.com/minhducn14/viact-auth.git](https://github.com/minhducn14/viact-auth.git)
**
---

## 🔧 Tech Stack

### Frontend
- ✅ ReactJS + Vite
- ✅ Material UI
- ✅ React Hook Form (custom hooks used internally)
- ✅ Google Login (`@react-oauth/google`)
- ✅ Axios

### Backend
- ✅ NestJS (MVC + DI)
- ✅ TypeORM
- ✅ MySQL
- ✅ JWT Authentication (Access + Refresh token)
- ✅ Bcrypt for password hashing

---

## ⚙️ Features

- User registration and login via Email/Password.
- Google OAuth login using `@react-oauth/google`.
- JWT-based authentication (Access and Refresh Tokens).
- Proper field validation and error handling.
- Responsive UI cloned from viAct.

---

## ▶️ Getting Started

### Prerequisites
- Docker + Docker Compose
- Node.js (if running manually)
- Git

---

## 🐳 Run with Docker

```bash
# Step 1: Clone the repo
git clone https://github.com/minhducn14/FullStackDeveloperTest
cd viact-clone

# Step 2: Build & run containers
docker-compose up --build
