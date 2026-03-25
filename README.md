# 🛋️ E-Commerce Furniture Sales Prediction

## 📌 Project Overview
This project focuses on predicting furniture product sales using machine learning techniques. The dataset contains information about product prices, discounts, and tags. The goal is to build models that can accurately predict the number of items sold.

---

## 🎯 Objectives
- Perform data preprocessing and cleaning  
- Apply feature engineering techniques  
- Train machine learning models  
- Evaluate model performance  
- Visualize predictions  

---

## 📂 Dataset
- **Name:** E-commerce Furniture Dataset  
- **Features:**
  - `price`
  - `originalPrice`
  - `discount`
  - `tagText`
  - `sold` (target variable)

---

## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 🔄 Project Workflow

### 1. Data Loading
- Dataset is loaded using Pandas

### 2. Data Cleaning
- Removed `$` symbols from price columns  
- Converted values to float  
- Handled missing values  

### 3. Feature Engineering
- Encoded categorical feature (`tagText`) using Label Encoding  

### 4. Train-Test Split
- Split dataset into training and testing sets (80:20)

### 5. Model Building
- Linear Regression  
- Random Forest Regressor  

### 6. Prediction
- Generated predictions using both models  

### 7. Evaluation Metrics
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- R2 Score  

---

## 📊 Results
- Random Forest performed better than Linear Regression  
- Achieved higher R2 score and lower error  

---

## 📈 Visualization
- Scatter plot of Actual vs Predicted values  
- Model comparison graph  

---

## 🧠 Conclusion
The Random Forest model provided better performance due to its ability to handle complex and non-linear relationships in the data. This project demonstrates how machine learning can be effectively used for sales prediction in e-commerce.

---

