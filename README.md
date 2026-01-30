# 🧠 Credit Card Fraud Detection using Machine Learning

---

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. Fraud detection is a critical real-world problem in the financial industry due to highly imbalanced datasets and the need for high recall and precision.

The main objective of this project is to build and evaluate machine learning models capable of accurately identifying fraudulent transactions while minimizing false positives.

---

## 📊 Dataset Information
- Dataset: Credit Card Fraud Detection Dataset  
- Total Transactions: 284,807  
- Fraud Transactions: ~0.17%  
- Features: 30 anonymized numerical features + Time + Amount  

This dataset is highly imbalanced, making it suitable for real-world fraud detection modeling.

---

## ⚙️ Technologies & Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-Learn  
- Imbalanced-Learn (SMOTE)  
- Joblib  

---

## 🧪 Machine Learning Workflow

### 🔹 Data Preprocessing
- Checked missing values  
- Feature scaling applied on Time and Amount  
- Train-Test split using stratification  

---

### 🔹 Handling Imbalanced Dataset
Used:
- SMOTE (Synthetic Minority Oversampling Technique)

This improved fraud detection recall significantly.

---

### 🔹 Models Implemented
- Logistic Regression (Baseline Model)  
- Logistic Regression with SMOTE  
- Random Forest Classifier (Final Production Model)  

---

## 📈 Model Evaluation Metrics
Since fraud detection is an imbalanced classification problem, accuracy alone is not reliable.

Metrics used:
- Precision  
- Recall  
- F1 Score  
- ROC-AUC Score  
- Precision-Recall Curve  
- PR-AUC Score  

---

## 🏆 Final Model Performance

| Model | ROC-AUC | PR-AUC | Fraud Recall |
|---|---|---|---|
| Logistic Regression | High | Medium | Low |
| Logistic + SMOTE | Higher | High | Good |
| Random Forest + SMOTE | Excellent | Excellent | Very High |

---

## 📉 Visualizations Included
- Class Distribution Plot  
- Precision-Recall Curve  
- Confusion Matrix  

---

## 💾 Model Saving
Final trained model saved using Joblib:

- `fraud_rf.pkl` → Trained Random Forest Model  
- `scaler.pkl` → Feature Scaler  

---

## 📂 Project Structure



---

## 🚀 How to Run This Project

### 1️⃣ Clone Repository


### 2️⃣ Install Dependencies

### 3️⃣ Run Jupyter Notebook


---

## 📌 Key Learning Outcomes
✔ Handling Highly Imbalanced Datasets  
✔ SMOTE Implementation  
✔ Fraud Detection Machine Learning Modeling  
✔ Business-Oriented Model Evaluation  
✔ Model Serialization for Production  

---

## 🎯 Future Improvements
- XGBoost Model Implementation  
- Deep Learning Neural Network Model  
- Streamlit Web Application Deployment  
- Real-time Fraud Detection API  

---

## 👨‍💻 Author
**Ali Haidar**  
BS Computer Science  
Machine Learning & Data Science Enthusiast
