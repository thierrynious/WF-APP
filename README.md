# 💰 Finance Manager App (WF-APP)

A full-stack finance management application built with **Spring Boot** and **React**.

This project demonstrates modern backend and frontend development, including authentication, REST APIs, and clean UI design.

---

## 🚀 Features

* 🔐 JWT Authentication (Login system)
* ➕ Create transactions
* ✏️ Edit transactions (Modal UI)
* ❌ Delete transactions
* 📊 Dashboard with financial overview
* 🔎 Search & filter transactions
* 📄 Pagination
* ⚡ REST API with Spring Boot

---

## 🛠 Tech Stack

### Backend

* Java 17+
* Spring Boot
* Spring Security (JWT)
* Spring Data JPA
* PostgreSQL (or H2 for dev)

### Frontend

* React (Vite)
* Axios
* CSS

---

## 📸 Screenshots

*(Füge hier später Screenshots ein)*

---

## ⚙️ Run locally

### Backend

```bash
./mvnw spring-boot:run
```

or

```bash
mvn spring-boot:run
```

---

### Frontend

```bash
cd finanzapp-frontend
npm install
npm run dev
```

---

## 📌 API Example

```http
POST /api/transactions
```

```json
{
  "title": "Salary",
  "amount": 2000,
  "date": "2025-10-30",
  "income": true
}
```

---

## 🧠 What I learned

* Building secure REST APIs with Spring Boot
* JWT authentication & authorization
* React state management
* API integration with Axios
* Clean project structure (backend + frontend)
* Debugging real-world bugs (e.g. income/expense logic)

---

## 📈 Future Improvements

* Charts (income vs expenses)
* Category system
* Export (PDF / CSV)
* Deployment (Docker + Cloud)

---

## 👨‍💻 Author

**Vincent Lameefu**

* GitHub: https://github.com/thierrynious

---

## ⭐ If you like this project

Give it a star ⭐
