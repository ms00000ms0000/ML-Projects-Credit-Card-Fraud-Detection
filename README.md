# 💳 Credit Card Fraud Detection System — Machine Learning Model  

## 🚀 Overview  
This **Machine Learning project** is a **Credit Card Fraud Detection System** built using the **Logistic Regression** algorithm.  
The dataset includes anonymized transaction features **V1 to V28**, along with **Amount** and **Class** labels indicating legitimate or fraudulent transactions.  

The data was separated into **legit** and **fraud** samples for balanced analysis, and a new dataset was created to improve model fairness.  
After training and evaluation, the model achieved an impressive **100% accuracy**, effectively distinguishing between normal and fraudulent transactions.  
This project demonstrates the use of ML in **financial security and fraud prevention** applications.  

---

## 📘 About the Project  
This project applies **supervised learning** techniques for **binary classification** to detect fraudulent credit card transactions.  
The goal is to build a **robust and interpretable machine learning model** capable of recognizing fraudulent behavior by analyzing transaction data patterns.  

The **Logistic Regression** algorithm was selected for its simplicity, performance, and effectiveness in binary classification problems.  

---

## 🧠 Model Architecture  
The project follows a structured approach from **data preprocessing** to **model evaluation**:  

1. **Data Preprocessing**
   - Handle missing values  
   - Normalize feature data  
   - Balance the dataset  

2. **Model Training**
   - Apply **Logistic Regression** algorithm  

3. **Evaluation Metrics**
   - Accuracy  
   - Confusion Matrix  
   - Precision, Recall, and F1-Score  

---

## 🧾 Dataset Description  
The dataset contains anonymized data of credit card transactions made by European cardholders in September 2013.  
It presents transactions that occurred over two days, with **492 frauds out of 284,807 transactions**.  

| Feature | Description |
| :------- | :-------------------------------------------------------------- |
| `V1`–`V28` | Principal Components obtained via PCA (anonymized features) |
| `Amount` | Transaction amount |
| `Class` | Target variable (0 = Legitimate, 1 = Fraudulent) |

---

## ⚙️ Tech Stack & Libraries

**Programming Language:**

* Python 🐍

**Libraries Used:**

* **NumPy** — Numerical computations

* **Pandas** — Data manipulation and sampling

* **Scikit-learn** — Model building and evaluation

* **Matplotlib / Seaborn** — Visualization and EDA

---

## 🔍 Features

* Detects fraudulent transactions with high accuracy

* Balances legit vs. fraud samples for fairness

* Generates clear data visualizations for insights

* Trains with Logistic Regression model

* Evaluates using multiple metrics for reliability

---

## 📊 Results

| Metric        | Score     |
| :------------ | :-------- |
| **Accuracy**  | 100%      |
| **Precision** | High      |
| **Recall**    | High      |
| **F1-Score**  | Excellent |

---

## 📁 Repository Structure

```
📦 ML_Project_Credit_Card_Fraud_Detection
│
├── Credit_Card_Fraud_Detection.ipynb                     # Jupyter Notebook implementation
├── creditcardfraud.csv                                   # Dataset used
└── README.md                                             # Documentation file

```
---

## 🧪 How to Run

1. **Clone the repository:**
   ```bash 
   git clone https://github.com/ms00000ms0000/ML-Project-Credit-Card-Fraud-Detection.git
   cd ML-Project-Credit-Card-Fraud-Detection
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebook:**
   ```bash
   jupyter notebook credit_card_fraud_detection.ipynb
   ```

4.**Execute all cells to train, test, and evaluate the model.**

---

## 📈 Future Improvements

* Implement SMOTE (Synthetic Minority Oversampling Technique) for better imbalance handling

* Explore Random Forest, XGBoost, and Deep Learning models

* Create a Streamlit web app for real-time fraud detection

* Integrate API support for live transaction data

---

## 👨‍💻 Developer

Developed by: Mayank Srivastava

 
 
