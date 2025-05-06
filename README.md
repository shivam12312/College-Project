Academic Project – Django Web Application
This repository contains a Django-based web application developed as part of an academic project at BCIIT. The app manages user interactions and serves multiple static and dynamic pages like home, faculty, and facilities.
Features
- User-friendly frontend with HTML/CSS templates
- Dynamic views for different pages (e.g., faculty details)
- Django admin panel integration
- SQLite database backend
- Static file handling (CSS, images)
Project Structure
├── manage.py
├── db.sqlite3
├── bciit_academic_project/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── testapp/
│   ├── migrations/
│   ├── templates/
│   │   ├── home.html
│   │   ├── faculty.html
│   │   └── ...
│   ├── static/
│   │   ├── css/
│   │   └── images/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
Setup Instructions
1. Clone the repository:

   git clone https://github.com/yourusername/bciit_academic_project.git
   cd bciit_academic_project
2. Create and activate a virtual environment:

   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install dependencies:

   pip install django
4. Run the project:

   python manage.py runserver
5. Access:

   Open your browser and visit: http://127.0.0.1:8000/
License
This project is for academic purposes.
