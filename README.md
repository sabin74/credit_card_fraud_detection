# 💳 Credit Card Fraud Detection

Detect fraudulent credit card transactions using both **supervised** and **unsupervised** machine learning techniques.

---

## 📁 Dataset

**Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Records:** 284,807  
- **Frauds:** 492 (0.172%)  
- **Features:** 30 anonymized PCA features + Time + Amount  
- **Target Variable:** `Class` (1 = Fraud, 0 = Not Fraud)

---

## 🧰 Tools and Libraries

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- imbalanced-learn (for supervised version)
- Joblib (for saving models)

---

## 🧠 Approaches

### ✅ Supervised Learning  
Detect fraud using labeled data. Algorithms used:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

### ✅ Unsupervised Learning  
Detect fraud as anomalies without using labels in training. Algorithms used:
- Isolation Forest
- One-Class SVM
- Local Outlier Factor
