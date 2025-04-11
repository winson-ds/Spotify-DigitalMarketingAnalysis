# Spotify App Review Analysis

This project focuses on large-scale sentiment analysis and exploratory data analysis (EDA) of user reviews for the Spotify app collected from the Google Play Store. The goal is to extract actionable insights to support product improvement and user experience enhancement.

## Project Overview

- **Application**: Spotify (com.spotify.music)
- **Data Source**: Google Play Store reviews
- **Number of Reviews Collected**: 500,000
- **Language**: English
- **Country**: Global (`country='us'` for scraping configuration)

## Features

### 1. Data Collection
- Web scraping of app reviews using the `google-play-scraper` library.
- Reviews are sorted by newest and retrieved in batches until reaching 500,000 records.

### 2. Exploratory Data Analysis (EDA)
- Cleaning and preprocessing of review text.
- Visualization of rating distributions, review lengths, and temporal trends.
- Identification of frequent keywords and themes using NLP techniques.

### 3. Sentiment Analysis
- Labeling of reviews into sentiment classes (Positive, Neutral, Negative).
- Dataset split into training (80%), validation (10%), and testing (10%).
- Model training using pre-trained transformer-based language models (e.g., BERT).
- Evaluation using accuracy, precision, recall, and F1-score.

### 4. Insight & Recommendation
- Aggregated sentiment trends by time and version.
- Highlight of major pain points and feature requests.
- Strategic recommendations for app improvement based on user sentiment.
