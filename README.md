# 💬 Social Media Sentiment Analysis (Sentiment140 Dataset)

Analyze how people feel about topics or brands using Twitter data — applying Natural Language Processing (NLP) and Machine Learning techniques.

---

## 📊 Project Overview

**Objective:**  
Measure public sentiment (positive vs. negative) from tweets using the [Sentiment140 dataset](https://www.kaggle.com/datasets/kazanova/sentiment140).

**Key Tasks:**
- Data cleaning and preprocessing (remove noise, stopwords, duplicates)
- Text vectorization using **TF-IDF**
- Model training with **Naive Bayes**, **Logistic Regression**, and **SVM**
- Evaluation with accuracy, F1-score, and confusion matrix
- Sentiment trend visualization (over time, by hashtag, etc.)

---

## 🧰 Technologies Used

| Category | Tools |
|-----------|-------|
| Language | Python |
| NLP Libraries | NLTK, TextBlob |
| ML Models | Scikit-learn (Naive Bayes, Logistic Regression, SVM) |
| Visualization | Matplotlib, Seaborn, WordCloud |
| Dataset | [Sentiment140 on Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140) |

---

## ⚙️ Steps Performed

1. **Data Loading & Cleaning**
   - Parsed CSV file, assigned column names
   - Converted date column and removed duplicates

2. **Text Preprocessing**
   - Removed URLs, mentions, punctuation, and stopwords
   - Tokenized and lemmatized words

3. **Feature Extraction**
   - Used TF-IDF vectorizer (`max_features=5000`)

4. **Model Training & Evaluation**
   - Compared **Naive Bayes**, **Logistic Regression**, and **SVM**
   - Logistic Regression achieved best accuracy: **78.18%**

5. **Visualization & Insights**
   - Sentiment over time (daily average)
   - Top positive and negative hashtags
   - Word clouds for positive/negative tweets

---

## 📈 Results

| Model | Accuracy | F1-Score |
|--------|-----------|-----------|
| Naive Bayes | 0.76 | 0.76 |
| Logistic Regression | **0.78** | **0.79** |
| SVM | 0.78 | 0.78 |

