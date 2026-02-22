# 📊 Telco Customer Churn Analytics & Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-orange.svg)
![Machine Learning](https://img.shields.io/badge/Focus-Classification-green.svg)

## 📌 Project Overview
Customer churn occurs when customers stop doing business with a company. For telecommunications companies, retaining existing customers is often more cost-effective than acquiring new ones. 

This project implements a **Random Forest Classifier** to predict the likelihood of customer attrition. By analyzing patterns in contract types, monthly charges, and tenure, the model identifies high-risk customers, allowing businesses to take proactive retention measures.



## 🗂️ Dataset Description
The model uses the **IBM Telco Customer Churn dataset**, which includes:
- **Demographics:** Gender, age range, and if they have partners/dependents.
- **Services:** Phone, multiple lines, internet, online security, streaming TV, etc.
- **Account Info:** Tenure, contract type, payment method, monthly charges, and total charges.
- **Target:** `Churn` (Yes/No) - Whether the customer left within the last month.

## 🛠️ Technical Implementation
### Data Preprocessing
- **Feature Engineering:** Converted `TotalCharges` to numeric and handled missing values.
- **Categorical Encoding:** Used `LabelEncoder` to transform text data into machine-readable formats.
- **Feature Scaling:** Applied `StandardScaler` to ensure all features contribute equally to the model's decision-making.

### The Model
I chose the **Random Forest Classifier** because:
1. It handles non-linear relationships well.
2. It is robust to outliers.
3. It provides **Feature Importance**, showing exactly which factors drive churn.

---

## 👤 Author

**Sachu Mon Puthenpuraickkal Sajeev** *Master in Computer Science (Data Analytics and Artificial Intelligence)* **TSI University (Transport and Telecommunication Institute)**

---
### Prerequisites
Ensure you have Python installed. You can install the necessary libraries using:
```bash
pip install -r requirements.txt
