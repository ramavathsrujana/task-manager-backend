# Task Manager API (Backend)

## Project Overview
This is the backend for the Task Manager application, built using Django and Django REST Framework.
It provides RESTful APIs to perform CRUD operations on tasks.

## Tech Stack
- Python
- Django
- Django REST Framework
- SQLite

## API Endpoints
- GET /api/tasks/ — List all tasks
- POST /api/tasks/ — Create a task
- PUT /api/tasks/{id}/ — Update a task
- DELETE /api/tasks/{id}/ — Delete a task

## How to Run Backend Locally

1. Clone the repository
2. Navigate to the backend folder
3. Create and activate virtual environment:
   python -m venv venv
   venv\Scripts\activate

4. Install dependencies:
   pip install -r requirements.txt

5. Apply migrations:
   python manage.py migrate

6. Start server:
   python manage.py runserver

7. Open:
   http://127.0.0.1:8000/api/tasks/

## Notes
- This backend is designed to be consumed by a React frontend.
- Backend deployment was explored; free-tier hosting limitations apply.
