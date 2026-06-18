# Twitter Sentiment Analysis

## Note

Due to GitHub's web upload size limitations, `Twitter_sentiment_analysis.ipynb` and `vectorizer.pkl` are not included in this repository.

## Project Overview

This project is a Twitter Sentiment Analysis web application built using Machine Learning, Natural Language Processing (NLP), and Streamlit.

The application predicts whether a tweet or text is Positive or Negative. It can also fetch recent tweets from a Twitter user and analyze their sentiments.

## Features

* Analyze sentiment of custom text input
* Fetch tweets from a Twitter username
* Predict Positive or Negative sentiment
* Text preprocessing using NLP techniques
* Interactive Streamlit web application

## Technologies Used

* Python
* Streamlit
* Scikit-learn
* NLTK
* TF-IDF Vectorizer
* NTScraper

## Machine Learning Pipeline

1. Data Collection
2. Text Preprocessing
3. Stopword Removal
4. Porter Stemming
5. TF-IDF Vectorization
6. Model Training
7. Sentiment Prediction
8. Streamlit Deployment

## Project Structure

```
Twitter-Sentiment-Analysis/
│
├── app.py
├── Twitter_sentiment_Analysis.ipynb
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
└── README.md
```

## Installation

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

## Future Improvements

* Add Neutral sentiment prediction
* Improve UI design
* Support more languages
* Add visual analytics dashboard
