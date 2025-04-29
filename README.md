# 📰 Fake News Detection using Machine Learning

This project aims to classify news articles as **Real** or **Fake** using Natural Language Processing (NLP) and a supervised machine learning model.

## 📌 Features
- Text preprocessing using NLTK
- TF-IDF vectorization
- Model training using Logistic Regression
- Evaluation metrics: accuracy, confusion matrix, etc.
- Optional: Web app with Streamlit/Flask for live predictions

## 📂 Dataset
Dataset used: [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

## 📊 Libraries Used
- pandas, numpy
- sklearn
- nltk
- joblib
- streamlit (optional for app)

## 🧠 Model
The machine learning pipeline involves:
- Removing punctuation, stopwords
- Tokenizing the text
- TF-IDF Vectorizer
- Logistic Regression for classification

## 📈 Results

Accuracy: 93%

Precision: 91%

F1-Score: 92%

## 📌SCREENSHOTS

![image](https://github.com/user-attachments/assets/d1210249-3e44-4f2b-a451-7aebedcb42de)


## 🚀 How to Run
```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
pip install -r requirements.txt
jupyter notebook notebook/fake_news_detection.ipynb
