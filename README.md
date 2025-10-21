# Interconnect Telecom Churn Prediction

## Overview
This project predicts **customer churn** for the telecom company **Interconnect** to help retain clients through targeted offers and promotions. Using customer, contract, and service data, I built a machine learning model to identify which users are most likely to leave.

---

## Data
The dataset includes:
- **contract.csv** — contract details  
- **personal.csv** — client demographics  
- **internet.csv** — internet service info  
- **phone.csv** — telephone service info  

Each record is linked by a unique **`customerID`**.

---

## Process
1. **Data Cleaning & Merging** – handled missing values, duplicates, and inconsistencies.  
2. **Feature Engineering** – created new features to capture service usage and contract patterns.  
3. **EDA** – explored churn trends by contract type, tenure, and payment method.  
4. **Modeling** – trained multiple models and selected the best performer.  

---

## Model
- **Algorithm:** LightGBM  
- **AUC-ROC:** 0.85  
- **Accuracy:** 0.80  

**Key Insight:**  
Clients with **month-to-month contracts** and **fewer add-on services** were most likely to churn.

---

## Tools
Python • Pandas • NumPy • Scikit-learn • LightGBM • Matplotlib 
