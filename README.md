# 📰 Fake News Detection System

A comprehensive **Natural Language Processing (NLP)** project for automatically classifying news articles as **Fake** or **Real** using **Machine Learning** and **Deep Learning** techniques.

---

## ✨ Project Overview

The rapid spread of misinformation on digital platforms makes automated fake news detection an essential task.  
This project aims to develop an end-to-end text classification system that analyzes news content and predicts whether a given article is **fake** or **real**.

Both **classical machine learning models** and **deep learning models** are implemented and compared to evaluate their effectiveness on textual data.

---

## 🧠 Models Implemented

### 🔹 Classical Machine Learning
- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)

> TF-IDF feature representation is used for all classical models.

### 🔹 Deep Learning
- Long Short-Term Memory (LSTM)
- BERT *(planned / ongoing)*

> LSTM models are trained using tokenized and padded text sequences.

---

## 🔧 Feature Engineering & Preprocessing

- Text normalization (lowercasing)
- Removal of punctuation and special characters
- Noise and whitespace cleaning
- TF-IDF vectorization (for ML models)
- Tokenization & padding (for LSTM)

---

## 📊 Evaluation Metrics

Models are evaluated using the following performance metrics:

- Accuracy  
- Precision  
- Recall  
- F1-Score  

Comparative analysis is performed to assess the strengths of classical ML models versus deep learning approaches.

---

## 📈 Key Findings

- **SVM with TF-IDF** achieved the highest classification performance.
- The **LSTM model**, while capable of learning sequential patterns, showed lower accuracy due to limited training epochs and computational constraints.
- Results indicate that classical ML models can outperform deep learning approaches on well-structured text datasets.

---

## 🖥️ User Interface

- A **Streamlit-based web interface** is planned to allow users to input news text and receive real-time predictions.

---

## 🛠️ Technologies Used

- Python 3.10  
- pandas, numpy  
- scikit-learn  
- TensorFlow / Keras  
- Jupyter Notebook  
- Git & GitHub  

---

## 📁 Project Structure

fake_news_project/
├── notebooks/
│   └── fake_news.ipynb      # Data preprocessing, ML & LSTM training notebook
├── requirements.txt         # Project dependencies
├── README.md                # Project documentation
└── .gitignore               # Ignored files and folders

---

