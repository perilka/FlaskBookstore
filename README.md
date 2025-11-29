# FlaskBookstore
[![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/flask-2.3%2B-green)](https://flask.palletsprojects.com/)

Full-featured online bookstore built with Flask: user auth, catalog, cart, orders, reviews and JSON data import.

## Features
- Registration / login with phone + email
- Book catalog with genres and search
- Shopping cart + order history
- Reviews and ratings
- One-click data import from JSON (`migrate_books.py`)

## Stack
- Flask + SQLAlchemy
- Flask-Login + WTForms
- Jinja2 + Bootstrap
- SQLite (easy switch to PostgreSQL)

## Run
```bash
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
python migrate_books.py
python app.py
```
Open http://127.0.0.1:5000
