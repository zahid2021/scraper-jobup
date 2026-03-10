# Scraper - jobup

This scraper extracts job listings from jobup website and saves them directly to a MySQL database.

## Features
- Scrapes job listings from website
- Parses structured data using LLM (Groq API)
- Saves directly to MySQL database
- Skips already processed jobs (no duplicates)
- Auto-retry on API quota limits

## Setup
1. Install dependencies:
   pip install -r requirements.txt

2. Create .env file:
   DB_HOST=localhost
   DB_USER=your_db_user
   DB_PASSWORD=your_db_password
   DB_DATABASE=job_portal_db
   GROQ_API_KEY=your_groq_api_key

3. Run:
   python3 main.py
