# Timpor - Graduation Project

*Timpor* is an AI-powered web platform to help university students manage academic tasks: smart scheduling, personalized reminders, performance analysis, and study-path suggestions.

## Features
- Smart scheduling (ML-based)
- Task CRUD and deadlines
- Performance dashboard & analytics
- Academic recommendations
- Notifications (email/push)

## Tech Stack
- Backend: Python (Flask)
- AI/Data: Python (NumPy, Pandas, Scikit-learn, TensorFlow/Keras)
- Database: MySQL / MariaDB / MongoDB
- Frontend: HTML, CSS, JavaScript, Bootstrap
- Version Control: Git / GitHub

## Repo Structure (suggested)
- backend/ — Flask API
- frontend/ — HTML/CSS/JS
- ai/ — Notebooks & ML models
- database/ — ERD & SQL scripts
- docs/ — Project plan, reports, demo files

## Quick start (local)
```bash
# clone repo
git clone https://github.com/YOURUSERNAME/Timpor_graduation_project.git
cd Timpor_graduation_project

# backend example
cd backend
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows
pip install -r requirements.txt
flask run
