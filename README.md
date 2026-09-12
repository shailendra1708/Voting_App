# 🗳️ Voting App

### Create. Vote. See what people think.

A full-stack voting application where users can create polls, choose from available options, cast their vote, and view the results.

Built as a practical full-stack project to understand how a modern frontend, REST API, backend services, and relational database work together.

<p align="center">
  <img src="screenshots/Created%20Poll.png" alt="Voting App - Created Poll" width="850">
</p>

---

## ⚡ The Idea

Most polling apps look complicated.

I wanted to build something simple:

> **Create a question → Add options → Let people vote → See the results.**

The project focuses on the complete flow of data — from the Angular interface to the Spring Boot API and finally into MySQL.

---

## ✨ Features

- 📝 Create polls
- 🔘 Add multiple voting options
- 🗳️ Cast votes
- 📊 Track voting results
- 💾 Persist data using MySQL
- 🔗 REST API powered by Spring Boot
- ⚡ Angular-based frontend
- 🔄 Real-time interaction between frontend and backend
- 🧩 JPA/Hibernate database integration

---

## 🖥️ Preview

### Create a Poll

<p align="center">
  <img src="screenshots/Created%20Poll.png" alt="Created Poll" width="850">
</p>

### Database Results

<p align="center">
  <img src="screenshots/Result%20database.png" alt="Voting Data in MySQL Database" width="850">
</p>

---

## 🧠 How It Works

```text
                    USER
                     │
                     ▼
            ┌─────────────────┐
            │ Angular Frontend│
            └────────┬────────┘
                     │
                     │ HTTP Requests
                     ▼
            ┌─────────────────┐
            │  Spring Boot    │
            │    REST API     │
            └────────┬────────┘
                     │
                     │ JPA / Hibernate
                     ▼
            ┌─────────────────┐
            │      MySQL      │
            │    Database     │
            └─────────────────┘
