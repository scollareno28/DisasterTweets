# Disaster Tweets Classification using Natural Language Processing

This project focuses on using Natural Language Processing (NLP) techniques to classify tweets related to disaster events. Given a tweet, the model predicts whether it describes a real disaster or not.

The objective is to help emergency response teams quickly identify and prioritize urgent information during natural disasters by filtering relevant tweets in real-time.



## Project Overview

In times of natural disasters, social media platforms like Twitter are often flooded with real-time information. However, not all tweets are relevant or actionable. This project builds a machine learning pipeline that:
- Processes and cleans raw tweet text
- Converts text into numerical features
- Trains a classification model to detect disaster-related tweets
- Evaluates and predicts on unseen data

The notebook (`disaster-natural-language-processing.ipynb`) guides through the entire workflow from preprocessing to model evaluation.

## Dataset

The dataset consists of labeled tweets with:
- `text`: The tweet content
- `target`: 1 if the tweet is about a real disaster, 0 otherwise



## Features

- **Text Preprocessing:**
  - Lowercasing
  - Removing URLs, HTML tags, special characters, punctuation
  - Tokenization and lemmatization
  - Stopword removal

- **Feature Engineering:**
  - Bag of Words (BoW)
  - TF-IDF vectorization
  - (Optional) Word embeddings (Word2Vec, GloVe)

- **Model Building:**
  - Logistic Regression
  - Random Forest
  - Support Vector Machines (SVM)
  - (Optional) LSTM or CNN models for text

- **Model Evaluation:**
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC-AUC Score

- **Visualization:**
  - Word clouds
  - Data distribution plots
  - Confusion matrices

## Results

The best performing model achieved the following results:
79% accuracy but in the Kaggle competition it was 74%
- **F1-Score:** 91.5%

The model demonstrated strong generalization capability, successfully distinguishing disaster-related tweets from normal tweets.


