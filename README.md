# Sentiment Analysis on Spotify Reviews using LSTM, GRU, and SimpleRNN

This project performs sentiment analysis on user reviews from the Spotify app using deep learning models including LSTM, GRU, and SimpleRNN. The goal is to classify reviews into three categories: positive, neutral, or negative.

## Tech Stack

* Python
* TensorFlow / Keras
* Google Colab

## Dataset

User reviews from the Spotify app (scraped from Google Play Store using Google Play Scraper)

## Training Scheme

### 1. First scheme

* **Algorithm**: LSTM (64 units)
* **Data Split**: 80/20
* **Embedding**: 64 dimensions
* **Dropout**: 0.2
* **Dense Layer**: 32 units

### 2. Second scheme

* **Algorithm**: GRU (64 units)
* **Data Split**: 70/30
* **Embedding**: 64 dimensions
* **Dropout**: 0.2
* **Dense Layer**: 32 units

### 3. Third scheme

* **Algorithm**: SimpleRNN (32 units)
* **Data Split**: 80/20
* **Embedding**: 32 dimensions
* **Dropout**: 0.5
* **Dense Layer**: 16 units

