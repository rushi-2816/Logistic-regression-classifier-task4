# 🧠 Task 4 – Logistic Regression (AI/ML Internship)

## 🎯 Objective
Build a binary classification model using Logistic Regression.

## 🛠 Tools
- Python, Pandas, Scikit-learn, Matplotlib

## 📊 Dataset
- Breast Cancer Wisconsin (Malignant = 0, Benign = 1)  
- 📎 [Download Dataset CSV](breast_cancer_dataset.csv)

## 🔧 Steps
1. Load dataset
2. Train-test split
3. Standardize features
4. Train logistic model
5. Evaluate (confusion matrix, precision, recall, ROC-AUC)
6. Plot ROC curve

## 📈 Output
```
Precision: 0.97
Recall: 0.94
ROC-AUC: 0.99
```

## ❓ Interview Q&A

**1. Logistic vs Linear Regression?**  
Logistic: classification + sigmoid. Linear: regression.

**2. What is sigmoid?**  
Maps value to 0-1: `1 / (1 + e^-z)`

**3. Precision vs Recall?**  
Precision = correct positives / all predicted positives  
Recall = correct positives / all actual positives

**4. ROC-AUC?**  
ROC: curve of TPR vs FPR.  
AUC: area under ROC curve (0–1)

**5. Confusion Matrix?**  
Table of TP, FP, FN, TN.

**6. Class imbalance?**  
Use precision, recall, F1, AUC instead of accuracy.

**7. Threshold tuning?**  
Change default 0.5 to improve precision/recall tradeoff.

**8. Multi-class with Logistic?**  
Yes, using One-vs-Rest or multinomial.

