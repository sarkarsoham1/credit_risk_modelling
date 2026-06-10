# Credit Risk Modeling & Default Prediction

## 📌 Overview

This project focuses on predicting customer default risk using statistical feature engineering and interpretable modeling techniques. The goal is to build a robust and explainable model that can effectively distinguish between defaulters and non-defaulters.

---

## 🎯 Problem Statement

Financial institutions face significant losses due to loan defaults. This project aims to:

* Identify high-risk customers
* Improve decision-making for credit approval
* Enhance risk segmentation using data-driven insights

---

## 📊 Dataset

The dataset contains customer-level financial and demographic information, including:

* Credit history
* Income details
* Loan attributes
* Behavioral indicators

---

## ⚙️ Approach

### 1. Data Preprocessing

* Handled missing values and inconsistencies
* Encoded categorical variables
* Scaled numerical features where required

### 2. Feature Engineering

* Applied Weight of Evidence (WoE) transformation
* Used Information Value (IV) for feature selection
* Removed multicollinearity using VIF

### 3. Model Development

* Built a classification model for default prediction
* Ensured stability and generalization across data splits

### 4. Evaluation

* Compared model performance across segments
* Analyzed overfitting and generalization gap

---

## 📈 Key Insights

* Strong separation achieved between high-risk and low-risk customer segments
* Reduced redundant features significantly, improving model stability
* Identified critical drivers of default risk using statistical measures
* Improved consistency of predictions across different customer groups

---

## 🧠 Key Learnings

* Importance of interpretable models in financial applications
* Role of feature engineering in improving model performance
* Practical challenges in handling real-world tabular data

---

## 📁 Project Structure

```
credit-risk-model/
│
├── notebook/
│   └── credit_risk_model.ipynb
│
├── artifacts/
│   └── model_data.joblib
│
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

* Implement monotonic binning for better WoE stability
* Build a complete credit scorecard
* Deploy model using a simple API interface

---

## 📬 Contact

If you have any questions or suggestions, feel free to connect.
