# movie_recommendation_system

🎬 IMDb Movie Recommendation System (2024) This project is a content-based movie recommendation system that suggests similar movies based on the input storyline. It uses TF-IDF vectorization and cosine similarity on movie plot descriptions scraped from IMDb (2024 feature films). The web interface is built using Streamlit.

🚀 Features

Scrapes movie data (titles & storylines) from IMDb's 2024 feature film list using Selenium.
Cleans and processes text using NLP (NLTK) for accurate matching.
Builds a TF-IDF matrix to capture story semantics.
Uses cosine similarity to find and recommend top 5 similar movies.
Interactive web app using Streamlit for user input and live recommendations.
📁 Project Structur 📂 IMDB-Movie-Recommendation-System-2024 ├── imdb_movies_2024.csv ├── preprocess_and_model.py ├── imdb_scraper.py ├── requirements.txt └── README.md

🧹 Text Preprocessing Lowercasing Removing punctuation and numbers Tokenization Stopword removal using NLTK

🛠 Technologies Used Python Pandas, NumPy NLTK Scikit-learn Selenium (for web scraping) Streamlit (for frontend)

📦 Dataset The dataset imdb_movies_2024.csv is generated using imdb_scraper.py by scraping IMDb's 2024 feature films. It contains: Title: Movie title Description: Movie storyline
