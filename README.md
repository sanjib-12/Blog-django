# 📝 Django Blog

A modern, user-friendly blog application built with **Django**, tailored for developers and content creators who value simplicity, performance, and design. Write, manage, and share your thoughts seamlessly—with built-in authentication, commenting, and a responsive layout.

![Django Blog Screenshot](https://img.shields.io/badge/Built%20With-Django-blue?style=flat-square) ![License: MIT](https://img.shields.io/badge/license-MIT-green?style=flat-square)

---

## 🚀 Features

- 🔐 **User Authentication** – Secure login, registration, and logout
- ✍️ **Blog Management** – Create, edit, and delete blog posts easily
- 💬 **Comment System** – Let users engage via comments
- 📱 **Responsive UI** – Mobile-friendly using Bootstrap
- 🛠️ **Admin Panel** – Manage everything via Django admin
- 💾 **SQLite** – Lightweight database for easy development

---

## 📋 Table of Contents

- [🛠️ Prerequisites](#️-prerequisites)
- [⚙️ Installation](#️-installation)
- [📖 Usage](#-usage)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

---

## 🛠️ Prerequisites

Before you begin, ensure you have the following installed:

- **Python** ≥ 3.8  
- **pip** – Python package manager  
- **Git** – Version control  
- **Virtualenv** – (Recommended) to isolate Python environments

---

## ⚙️ Installation

Clone and run the project locally in a few simple steps:

```bash
# 1. Clone the repo
git clone https://github.com/sanjib-12/Django-blog.git
cd Django-blog

# 2. Set up a virtual environment
python -m venv env
source env/bin/activate       # Windows: env\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Apply migrations
python manage.py makemigrations
python manage.py migrate

# 5. Create a superuser for admin access
python manage.py createsuperuser

# 6. Run the development server
python manage.py runserver

```

##  📖 Usage
**Admin Panel**: Access via http://localhost:8000/admin

**Create Posts**: Log in, then create/edit posts from the dashboard

**Commenting**: Authenticated users can add comments to posts

**Customization**: Modify templates in blog/templates/ or styles in blog/static/

## 🤝 Contributing

We welcome contributions to improve the project! To contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

Please adhere to the PEP 8 style guide and include tests where applicable.

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

*Built with ❤️ using Django and Bootstrap*