# 🛍️ Sultana E-commerce Store

**Sultana** is a modern, full-stack e-commerce web store built for a niche market. Built with Django and Tailwind CSS, the platform supports dynamic product listings, secure user authentication, a shopping cart system, Stripe payments, and responsive UI.

---

## 🚀 Features

- 🛒 Product Catalog (with categories & search)
- 👤 User Authentication (Login, Register, Logout)
- 🧺 Shopping Cart (session-based)
- 💳 Checkout with Stripe integration
- 🖼️ Product image uploads (local or Cloudinary/S3)
- 📦 Order management (per user)
- 🧠 Admin panel for managing inventory
- 💅 Responsive UI powered by Tailwind CSS

---

## 🧱 Tech Stack

| Layer      | Technology               |
|------------|--------------------------|
| Backend    | Django (Python)          |
| Frontend   | Tailwind CSS (via `django-tailwind`) |
| Database   | PostgreSQL               |
| Auth       | Django Auth / Allauth    |
| Payments   | Stripe                   |
| Storage    | Local (dev), S3/Cloudinary (prod) |
| Deployment | Heroku / Render / Railway|

---

## 📁 Project Structure

```bash
sultana-store/
│
├── ecommerce/           # Django project
├── store/               # Core app: products, cart, orders
├── users/               # Custom user logic (optional)
├── theme/               # Tailwind CSS app
├── templates/           # HTML templates
├── static/              # Compiled static files
├── media/               # Uploaded images
├── requirements.txt
└── manage.py
