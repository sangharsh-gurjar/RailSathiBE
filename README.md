# 🚉 RailSathiBE - Backend Assignment

This is a Dockerized **FastAPI** backend project using **PostgreSQL** as its database.

---

## 📦 Tech Stack

- **Backend**: FastAPI (Python 3.10)
- **Database**: PostgreSQL (via Docker)
- **Containerization**: Docker + Docker Compose
- **Environment Configuration**: `.env` file
- **API Docs**: Swagger UI (FastAPI built-in)

---

## 🚀 Getting Started

These instructions will get your backend running locally using Docker.

### ✅ Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/)

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/RailSathiBE.git
cd RailSathiBE
```
### 2. Create .env file

```
cp .env.example .env

```
### 3. Start Services

```
docker compose up --build
```
  or
```  
sudo docker compose up --build


```
