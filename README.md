# 🛍️ Amazon Review Sentiment Analysis

This project implements a machine learning pipeline to classify Amazon product reviews as positive or negative. It focuses on building a clean NLP workflow using scikit-learn and TF-IDF vectorization, with model tuning for performance optimization.

---

## 📌 Project Highlights

- Text preprocessing: tokenization, lowercasing, punctuation & stopword removal
- Feature extraction using **TF-IDF Vectorizer**
- Model training using **Logistic Regression**
- **Hyperparameter tuning** with `RandomizedSearchCV`
- Evaluation using accuracy, classification report, and confusion matrix

---

## 📊 Results

- Achieved ~75% accuracy on validation data
- Improved performance through randomized grid search

---

## 🧰 Tech Stack

- **Languages:** Python  
- **Libraries:** scikit-learn, Pandas, NLTK, NumPy, Matplotlib  
- **Techniques:** NLP, TF-IDF, Logistic Regression, Model Tuning

---

## 📁 Repository Structure

```bash
amazon-sentiment-analysis/
├── amazon_sentiment_analysis.ipynb     # Main notebook
└── README.md                           # Project overview and instructions
