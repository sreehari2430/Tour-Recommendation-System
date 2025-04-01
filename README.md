🌍 Tour Recommendation System


✨ Overview

The Tour Recommendation System is an AI-powered web application that suggests travel destinations based on user preferences. It leverages Generative AI (GenAI), NLP, and Large Language Models (LLMs) such as Google's Gemini to generate descriptions for recommended destinations. The system is built with Django (Python) and integrates a database to store user inputs and recommendations.

🔧 Features

💡 AI-Powered Destination Recommendations using NLP and LLM models.

🌍 Real-time Generation of Travel Descriptions with Gemini.

🌐 Web-Based Interface built with Django.

🛠️ Customizable Filters (e.g., budget, weather, interests).

👥 User Authentication & Profiles for personalized suggestions.

📝 Data Storage with an integrated database.

👨‍💻 Technologies Used

Backend: Django (Python), FastAPI (optional for AI endpoints)

AI Models: Google Gemini, NLP, LLM-based text generation

Database: PostgreSQL / SQLite

Frontend: HTML, CSS, JavaScript

APIs: Google Places API (optional for additional travel info)

Deployment: AWS / Render / Heroku (optional)

⚙️ Installation & Setup

🔄 Prerequisites

Python 3.8+

Virtual Environment (venv)

PostgreSQL / SQLite

Django Framework

🛠️ Setup Steps

Clone the repository

git clone https://github.com/sreehari2430/Tour-Recommendation-System.git
cd Tour-Recommendation-System

Create a virtual environment & activate it

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install dependencies

pip install -r requirements.txt

Setup database migrations

python manage.py migrate

Run the Django server

python manage.py runserver

Access the application at http://127.0.0.1:8000/

🏆 How It Works

User provides input on travel preferences (e.g., interests, budget).

The system processes input using NLP and LLM models.

Google Gemini generates a detailed description of the recommended destinations.

Results are displayed on the Django-based web interface.

Users can save or refine recommendations.

📊 Database Schema

Table

Fields

Users

id, name, email, password

Preferences

id, user_id, interests, budget

Destinations

id, name, description, rating

🌟 Future Enhancements

📺 Integration with Google Maps for interactive exploration.

💪 Personalized AI itineraries based on user history.

🌐 Multilingual support for international users.

🚀 Mobile app version (React Native / Flutter).

🌟 Contributing

We welcome contributions! Feel free to fork this repo, create a new branch, and submit a pull request.

✉ Contact

Sreehari VGitHub: @sreehari2430Email: your-email@example.com

🌟 Star this repo if you find it useful!
