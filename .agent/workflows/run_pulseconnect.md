---
description: Run the PulseConnect application (Backend & Frontend)
---

1. Start the Backend
   - Navigate to `backend` directory
   - Install dependencies: `pip install -r requirements.txt`
   - Seed database: `python seed.py`
   - Start server: `uvicorn main:app --reload` (runs on http://localhost:8000)

2. Start the Frontend
   - Navigate to `frontend` directory
   - Install dependencies: `npm install`
   - Start server: `npm run dev` (runs on http://localhost:5173)
