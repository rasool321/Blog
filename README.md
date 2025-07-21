# Blog Application using Flask

Welcome to the Blog Project – a simple and functional blogging platform built with the Flask web framework in Python.

Whether you're learning Flask or looking to build a basic full-stack application, this project serves as a great foundation.

---

## Features

- Create, read, and delete blog posts  
- User authentication with secure password hashing  
- Profile picture upload support using Pillow  
- Email functionality with Flask-Mail  
- SQLite database integration using SQLAlchemy  
- Clean and scalable project structure

---

## Prerequisites

Before running this project, ensure that the following tools are installed on your system:

- Python 3.x → [Download Python](https://www.python.org/downloads/)
- pip → Comes pre-installed with Python

---

## Installation

Follow these steps to set up the project on your local machine:

### 1. Clone the Repository
```bash
git clone https://github.com/rasool321/Blog.git
cd Blog
```

### 2. (Optional) Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

### 3. Install Required Packages
```bash
pip install -r requirements.txt
```

Or install manually:
```bash
pip install Flask Flask-WTF Flask-SQLAlchemy Flask-Bcrypt Flask-Login Pillow itsdangerous Flask-Mail
```

---

## Configuration

Before running the app, you need to configure environment variables. You can do this using a `.env` file or by setting them manually:

```env
SECRET_KEY=your_secret_key
SQLALCHEMY_DATABASE_URI=sqlite:///site.db
MAIL_SERVER=smtp.gmail.com
MAIL_PORT=587
MAIL_USE_TLS=True
MAIL_USERNAME=your_email@gmail.com
MAIL_PASSWORD=your_email_password_or_app_password
```

---

## Running the Application

Use the following command to start the Flask development server:

```bash
python run.py
```

Once running, open your browser and navigate to:

```
http://127.0.0.1:5000
```

---

## Tech Stack

| Technology         | Purpose                              |
|--------------------|--------------------------------------|
| Flask              | Web framework                        |
| Flask-WTF          | Form handling                        |
| Flask-SQLAlchemy   | ORM for database operations          |
| Flask-Bcrypt       | Password hashing                     |
| Flask-Login        | User authentication                  |
| Pillow             | Image processing (profile uploads)   |
| itsdangerous       | Token generation (e.g., password reset) |
| Flask-Mail         | Sending emails                       |

---

## Contributing

We welcome contributions. Follow these steps to get started:

1. Fork the repository  
2. Create a new branch  
```bash
git checkout -b feature/your-feature
```
3. Make your changes  
4. Commit your changes  
```bash
git commit -m "Add your feature"
```
5. Push to your branch  
```bash
git push origin feature/your-feature
```
6. Open a pull request

---

## Contact

Developed by Rasool

- GitHub: [@rasool321](https://github.com/rasool321)  
- Email: srasool6371@gmail.com
