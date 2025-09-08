# FinWise Scaffold

This scaffold provides a full-stack starter for the **FinWise** platform:
- Django backend (modular apps + DRF)
- React frontend (Vite + Tailwind)
- Docker + docker-compose for local dev

**Important:** This scaffold intentionally does NOT include your real API keys.  
Copy your keys into `backend/.env` before running.

Quick start (local, without Docker):
1. Backend:
   - `cd backend`
   - `python -m venv venv && source venv/bin/activate` (on Windows use `venv\Scripts\activate`)
   - `pip install -r requirements.txt`
   - Create `backend/.env` (see `.env.example`)
   - `python manage.py migrate`
   - `python manage.py createsuperuser`
   - `python manage.py runserver`

2. Frontend:
   - `cd frontend`
   - `npm install`
   - `npm run dev`

To run with Docker:
- `docker-compose up --build`

