# DRF eCommerce Site 🛒

An eCommerce platform built using **Django Rest Framework (DRF)**. This project provides a robust backend for managing products, orders, users, and payments, making it suitable for building scalable and feature-rich online stores.

## Features

### Core Functionalities
- **User Management**:
  - Registration and login (JWT-based authentication).
  - User profile management.
- **Product Management**:
  - List, view, and search for products.
  - Filter products by categories, price, and ratings.
- **Shopping Cart**:
  - Add, update, or remove items.
  - Persistent cart for logged-in users.
- **Order Management**:
  - Place and manage orders.
  - View order history and details.
- **Payment Integration**:
  - Integrates with payment gateways (e.g., Stripe or PayPal).
  - Secure payment processing.
- **Admin Panel**:
  - Add, update, and manage products, categories, and orders.
  - Analytics and reporting.


## Prerequisites

Before setting up the project, make sure you have the following installed:
- **Python 3.10+**
- **PostgreSQL** (or another supported database)
- **Node.js** (if frontend integration is planned)
- **pip** for Python package management

## Installation

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/drf-ecommerce.git
   cd drf-ecommerce
2. Create and activate a virtual environment:

```bash
python -m venv env
source env/bin/activate  # For Windows: env\Scripts\activate
3. Install dependencies:

```bash

pip install -r requirements.txt
4. Set up the database:

Create a PostgreSQL database.
Update the database settings in ecommerce/settings.py.
5. Apply migrations:

```bash
python manage.py makemigrations
python manage.py migrate
6. Create a superuser:
```bash
python manage.py createsuperuser
7. Run the development server:
```bash
python manage.py runserver
The server will be available at http://127.0.0.1:8000.

