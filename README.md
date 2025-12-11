# ChurnPrediction_NN_and_CNN
The objective of this project is to develop and compare **Neural Network (NN)** and **Convolutional Neural Network (CNN)** models to predict customer churn using a real-world telecom dataset. The project includes data preprocessing, feature engineering, model building, evaluation, and analysis.

---

## Project Overview

Customer churn prediction helps telecom companies identify customers likely to discontinue service.  
By building deep learning models on structured customer data, businesses can make informed retention strategies.


This project includes:

- Data cleaning & preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering & scaling  
- Neural Network model  
- Convolutional Neural Network model  
- Evaluation using multiple metrics  
- Comparison & insights for customer retention  

---

## Dataset

Dataset: **Telco Customer Churn (Kaggle)**  
Includes features such as:

- Customer tenure  
- Contract type  
- Payment method  
- Monthly & total charges  
- Internet & phone services  
- Additional subscriptions  
- Demographic details  

**Target Variable:**  
`Churn` → `1` (customer left) or `0` (customer stayed)

---

## Data Preprocessing

Steps performed:

- Handling missing values  
- Converting categorical data using:
  - Label Encoding  
  - One-Hot Encoding  
- Feature scaling (StandardScaler / MinMaxScaler)  
- Train-test split  
- EDA with visualizations:
  - Histograms  
  - Count plots  
  - Box plots  
  - Correlation heatmaps  

---

## Models Implemented

### **Model 1 — Neural Network (NN)**  
Built using TensorFlow/Keras or PyTorch:
- Dense layers  
- ReLU activation  
- Dropout (optional)  
- Sigmoid output for binary classification  

### **Model 2 — Convolutional Neural Network (CNN)**  
CNN applied on reshaped tabular data:
- Conv1D / Conv2D layers  
- MaxPooling layers  
- Flatten + Dense layers  
- Sigmoid output  

### Comparison Included:
- Which model performs better  
- Why based on dataset characteristics  
- Limitations and observations  

---

## Model Training & Evaluation

Metrics used:

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- AUC-ROC Curve  
- Confusion Matrix  

---

## How to Run the Project

1. Clone the repository:

```bash
git clone <repo-url>
cd MNIST-Digit-Classifier-PyTorch
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the .ipynb file 

---

## Summary

This project includes:

End-to-end churn prediction workflow

EDA + visualizations

Deep learning models (NN & CNN)

Evaluation + comparison

Insights for customer retention strategy

---
