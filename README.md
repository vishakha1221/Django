# 🚀 Django 5 Projects — By Example (Fifth Edition)

![Django](https://img.shields.io/badge/Django-5.0-green?style=flat&logo=django)
![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python)
![License](https://img.shields.io/badge/license-MIT-lightgrey)
![Status](https://img.shields.io/badge/status-Learning-orange)

Welcome to my learning journey through the book **📘 Django 5 By Example – Fifth Edition** by **Antonio Mele**. This repository contains hands-on code as I build powerful and production-ready Django applications, one chapter at a time.

---

## 🧠 Why This Repo?

> "Learning by doing is the best way to master Django."

- ✅ Learn Django 5 through real-world projects  
- ✅ Write clean, modular, production-grade code  
- ✅ Build reusable apps step-by-step  
- ✅ Explore advanced Django features like Channels, Celery, and Deployment  

---

## 📂 Projects Roadmap

| 📦 Chapter | 💻 Project                          | 📌 Topics Covered                        |
|------------|-------------------------------------|------------------------------------------|
| 01–03      | 📝 Blog App                         | Models, Views, Templates, Admin          |
| 04–06      | 👥 Social Website                   | Users, Authentication, Forms             |
| 07–09      | 🛒 E-Commerce Platform              | Cart, Checkout, Payments, Media Files    |
| 10–12      | 📰 Real-time News App               | Django Channels, WebSockets, Async       |
| 13+        | 🚀 Full Deployment                  | Gunicorn, Nginx, Docker, Heroku/AWS      |

---
## 💡 Tech Stack
🌐 Django 5.x
🐍 Python 3.10+
🛢️ PostgreSQL / SQLite
🧰 Bootstrap 5
🔌 Django Channels & WebSockets
📦 Celery + Redis
🐳 Dockerized (optional)
☁️ Deployed on Render/Heroku/VPS


## ⚙️ Setup Instructions

```bash
# 1. Clone the repo
git clone https://github.com/your-username/django5-by-example.git
cd django5-by-example/chapter-01

# 2. Create & activate virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
python manage.py migrate
python manage.py runserver
