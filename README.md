# 🎬 GT Movies Store

A full-stack Django web application that allows users to browse movies, authenticate securely, and interact with movie content through reviews. This project demonstrates core web development concepts including authentication, authorization, CRUD operations, database management, and deployment.

---

# 🚀 Project Overview

GT Movies Store is a Django-based web application designed and implemented to satisfy a set of user stories centered around usability, security, and real-world web app behavior.

Users can explore movies, create accounts, log in, and engage with movie content through reviews, all while respecting strict permission rules.

The application follows Django’s **Model–View–Template (MVT)** architecture and emphasizes clean separation of concerns, maintainability, and scalability.

---

# ✨ Features

## 🔐 Authentication & Authorization

- User registration, login, and logout
- Session-based authentication using Django’s built-in auth system
- Access control to restrict sensitive actions to logged-in users

## 🎥 Movie Browsing

- List of movies dynamically loaded from the database
- Individual movie detail pages with images, pricing, and reviews

## 📝 Reviews (CRUD)

- Create reviews *(authenticated users only)*
- Read reviews from all users
- Update reviews *(only by the review owner)*
- Delete / Report reviews with permission checks

## 🛡️ Permissions & Security

- Users can only edit or delete their own reviews
- Unauthorized actions automatically redirect users
- CSRF protection enabled on all forms

## 🌐 Deployment

- Deployed using PythonAnywhere
- Uses SQLite for compatibility with free-tier hosting
- Environment isolation via virtual environments

---

# 🧠 User Stories Implemented

- As a user, I can browse movies without logging in
- As a user, I can create an account and log in securely
- As a logged-in user, I can create movie reviews
- As a user, I can edit or delete my own reviews
- As a user, I cannot modify reviews created by others
- As a user, I can report inappropriate reviews so they are removed

Each feature was explicitly designed to fulfill these user stories.

---

# 🏗️ Tech Stack

**Backend:** Django (Python)  
**Frontend:** Django Templates, HTML, Bootstrap  
**Database:** SQLite  
**Authentication:** Django Auth  
**Deployment:** PythonAnywhere  
**Version Control:** Git & GitHub

---


# ⚙️ Local Setup Instructions

## Clone the Repository

```bash
git clone https://github.com/your-username/moviesstore.git
cd moviesstore
```

## Create Virtual Environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

## Install Dependencies

```bash
pip install django==5.0 pillow pymysql
```


## Apply Migrations

```bash
python manage.py migrate
```

## Create Superuser

```bash
python manage.py createsuperuser
```


## Run Server

```bash
python manage.py runserver
```



# 👤 Author
Zuhayr Kabir
