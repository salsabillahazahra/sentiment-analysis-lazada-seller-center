# 🛍️ Sentiment Analysis on Lazada Seller Center Information System

This repository contains the implementation of a sentiment analysis study titled:

> **"Utilization of Sentiment Analysis Techniques for Evaluating the Performance of Lazada Seller Center Information System"**

The research aims to evaluate user sentiment toward the Lazada Seller Center system by analyzing online reviews. The analysis applies text mining techniques and machine learning methods to classify sentiments into **positive** and **negative** categories.

---

## 📊 Project Overview

This project focuses on:
- **Collecting** and preprocessing review data from Lazada Seller Center.
- **Transforming** textual data using **Term Frequency–Inverse Document Frequency (TF–IDF)**.
- **Balancing** the dataset using **ADASYN (Adaptive Synthetic Sampling)** to handle class imbalance.
- **Classifying** sentiments using **Support Vector Machine (SVM)**.
- **Evaluating** model performance with metrics such as accuracy, precision, recall, and F1-score.

---

## 🧠 Methods and Techniques

| Stage | Description |
|-------|--------------|
| **1. Data Collection** | User reviews were collected from Lazada Seller Center platform. |
| **2. Text Preprocessing** | Includes tokenization, stopword removal, and case folding. |
| **3. TF–IDF Transformation** | Converts text data into numerical representation suitable for machine learning. |
| **4. ADASYN Oversampling** | Balances the dataset by generating synthetic samples for the minority class. |
| **5. SVM Classification** | Used for sentiment classification (positive vs. negative). |
| **6. Evaluation** | Model performance assessed using standard classification metrics. |

---

## 🧩 File Structure

📂 sentiment-analysis-lazada
│
├── 📁 data
│ └── dataset_lazada.csv # Raw dataset containing user reviews
│
├── 📁 notebooks
│ └── sentiment_analysis.ipynb # Main Jupyter Notebook for sentiment analysis
│
└── README.md # Project documentation



---

## 🧰 Tools and Libraries

- Python 3.x  
- pandas  
- scikit-learn  
- imbalanced-learn  
- matplotlib / seaborn  
- nltk  

---

## 📈 Results Summary

The implementation results show that:
- **TF–IDF** successfully represents textual features with significant weighting on important terms.  
- **ADASYN** effectively improved class balance between positive and negative reviews.  
- **SVM** achieved high accuracy in classifying sentiments, demonstrating good model performance for text-based analysis.

*(You can update this section later with your exact accuracy, precision, recall, and F1-score values.)*

---

## 🧾 Citation

If you use or refer to this project in your work, please cite as:

> Salsabillah Azahra (2025). *Utilization of Sentiment Analysis Techniques for Evaluating the Performance of Lazada Seller Center Information System*. STMIK IKMI Cirebon.

---

## 📬 Contact

**Author:** Salsabillah Azahra  
**Institution:** STMIK IKMI Cirebon  
**Program:** Information Systems 

---

> ⭐ Feel free to star this repository if you find it useful or inspiring!
