<h1 align="center">🗓️ PRIORITY PLANNER</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Django-5.2-darkgreen?style=flat-square&logo=django" alt="Django" />
  <img src="https://img.shields.io/badge/Render-Hosted-blue?style=flat-square&logo=render" alt="Render" />
  <img src="https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python" alt="Python" />
  <img src="https://img.shields.io/badge/PostgreSQL-Cloud DB-critical?style=flat-square&logo=postgresql" alt="PostgreSQL" />
  <img src="https://img.shields.io/github/license/shahrukh-1052/PRIORITY_PLANNER?style=flat-square" alt="License" />
</p>

---

## 🌟 Overview

> **Priority Planner** is a dynamic and minimalistic task management web application designed for productivity-focused users. It allows you to organize tasks, set due dates, assign priorities, and stay in control of your schedule.

This project is built using **Django 5.2** and deployed on **Render** using **PostgreSQL** for cloud production. It features an intuitive interface, robust authentication, and seamless deployment support.

---

## 🚀 Live Demo

<p align="center">
  <a href="https://priority-planner.onrender.com/" target="_blank">
    <img src="https://img.shields.io/badge/-🌐 View Deployed App-0D1117?style=for-the-badge&logo=render&logoColor=white" />
  </a>
</p>

---

## 🔥 Features

- 🔐 Secure User Authentication (Register / Login / Logout)
- 📌 Add, Update, Delete Tasks
- 🏷️ Set Task Priority (High, Medium, Low)
- 🗓️ Assign Due Dates and Sort by Deadlines
- 🧹 Clean and Responsive UI for all devices
- 💾 PostgreSQL Database (on production), SQLite (for dev)
- 🛡️ Environment-secure config via `.env`
- ⚙️ Static files managed by WhiteNoise for production

---

## 🧰 Tech Stack

| Layer         | Technology                            |
|---------------|----------------------------------------|
| 💻 Frontend      | HTML5, CSS3, Bootstrap (light)         |
| 🐍 Backend       | Python 3.11, Django 5.2                |
| 🛢️ Database      | SQLite (local), PostgreSQL (cloud)     |
| ☁️ Deployment    | Render.com                             |
| 🧊 Static Files  | WhiteNoise                             |
| 🔐 Env Manager   | python-dotenv                          |

---

## ⚙️ Local Development Setup

Follow these steps to run this project locally.

### ✅ Requirements
- Python 3.10+
- Git
- pip / pipenv / poetry
- PostgreSQL (optional for local DB testing)

### 🛠️ Installation

```bash
# 1. Clone the repository
git clone https://github.com/shahrukh-1052/PRIORITY_PLANNER.git
cd PRIORITY_PLANNER

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Setup environment variables
touch .env
# Add the following:
# SECRET_KEY=your-secret-key
# DEBUG=True
# DATABASE_URL=your-postgres-url (optional)

# 5. Run migrations
python manage.py migrate

# 6. Start development server
python manage.py runserver
