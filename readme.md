#  TweetKarr 👨🏻‍💻
**TweetKarr** is a minimalist tweet-posting web application built with **Django** and styled using **Tailwind CSS** and Bootstrap. Users can register, log in, create, edit, delete, and view tweets, with optional image attachments. The UI is responsive and designed for a clean, professional look.

---

## 🚀 Features

- User registration and login
- Create, edit, and delete tweets
- Optional image uploads with tweets
- Search functionality for tweets
- Mobile-friendly and modern UI
- Tailwind + Bootstrap for styling

---

## 📦 Requirements

Ensure you have Python 3.8+ and pip installed. Install dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt
```

---

## 🛠️ Setup Instructions

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/tweetkarr.git
   cd tweetkarr
   ```

2. **Create a virtual environment (recommended)**  
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**  
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional)**  
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**  
   ```bash
   python manage.py runserver
   ```

7. **Start Tailwind CSS (if using django-tailwind)**  
   In another terminal:
   ```bash
   python manage.py tailwind start
   ```

8. **Visit the app**  
   Go to: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 📁 Folder Structure

```
tweetkarr/
├── tweet/                 # Main Django app
├── templates/             # HTML templates
├── media/                 # Uploaded tweet images
├── theme/                 # Tailwind CSS theme app
├── requirements.txt       # Python dependencies
└── manage.py              # Django entry point
```

---

## 💡 Notes

- Admin Panel: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)
- Make sure `MEDIA_URL` and `MEDIA_ROOT` are set in `settings.py` for image uploads.

---

## 📷 Screenshots

Coming soon...

---

## 📝 License

This project is licensed under the MIT License.
