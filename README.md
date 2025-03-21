# 📰 Fake News Detection System

This project implements a robust **Fake News Detection** system using three machine learning models: **Naive Bayes**, **Random Forest**, and **LSTM**. The system classifies news articles as **Fake** or **Real** based on their textual content.

---

## 📌 Features

- Clean and preprocess news articles (lowercasing, stopword removal, stemming).
- Train and evaluate:
  - Naive Bayes
  - Random Forest
  - LSTM (with embedding and sequence padding)
- Visual performance comparison of models
- Confusion matrices and classification reports
- Supports custom input testing for new articles

---

## 📦 Dependencies

Make sure to install the following libraries before running the notebook:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn keras tensorflow

```

---

## 📂 Dataset

**Dataset used:** [Fake and Real News Dataset on Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

It contains two CSV files:
- `Fake.csv`
- `True.csv`

Each article is labeled accordingly and preprocessed before training:
- HTML tags and punctuation removed
- Lowercased text
- Tokenization and stopword removal
- Optional stemming for traditional models

---

## 🚀 Models & Performance

### 📊 Evaluation Report for Naive Bayes

- **Accuracy:** 94.19%
- **Precision:** 93.00%
- **Recall:** 94.92%
- **F1 Score:** 93.95%


### 📊 Evaluation Report for Random Forest ✅ *Best*

- **Accuracy:** 99.77%
- **Precision:** 99.72%
- **Recall:** 99.79%
- **F1 Score:** 99.75%


### 📊 Evaluation Report for LSTM

- **Accuracy:** 99.3%
- **Precision:** 99.44%
- **Recall:** 99.09%
- **F1 Score:** 99.26%


---

## 📁 Files Included

- `Fake_News_Detection.ipynb` – Jupyter Notebook containing:
  - Data Preprocessing
  - Model Training (Naive Bayes, Random Forest, LSTM)
  - Evaluation Metrics
  - Visualization & Testing Interface

- `Fake.csv`, `True.csv` – Dataset files *(must be downloaded separately from [Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset))*
