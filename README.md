# SCT_DS_3
# 🏦 Bank Marketing Prediction (Decision Tree)

## 📌 Project Overview
This project builds a Decision Tree classifier to predict whether a customer will subscribe to a term deposit based on demographic and behavioral data. The aim is to analyze patterns and improve marketing decision-making.

---

## 📂 Dataset
- Source: UCI Machine Learning Repository  
- Dataset: Bank Marketing Dataset  
- File used: `bank-full.csv`  
- Records: 45,000+ customer entries  
- Target Variable: `y` (subscription: yes/no)

---

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn
- Google colab 

---

## 🔧 Data Preprocessing
- Converted target variable (`y`) into numerical format (0/1)  
- Applied one-hot encoding to categorical variables  
- Checked for missing values and data consistency  

---

## 🤖 Model Building
- Algorithm: Decision Tree Classifier  
- Data split into training (80%) and testing (20%)  
- Controlled model complexity using `max_depth`  

---

## 📊 Model Evaluation
- Accuracy Score  
- Classification Report (Precision, Recall, F1-score)  
- Confusion Matrix visualization  

---

## 📈 Visualizations
- Confusion Matrix Heatmap  
- Decision Tree Visualization  
- Subscription Distribution Plot  

---

## 📊 Key Insights
- Customers with longer call duration are more likely to subscribe  
- Previous successful campaigns increase conversion probability  
- Job type and marital status influence decisions  
- Decision Tree helps interpret customer behavior effectively  

---
## 📁 Project Structure
📦 Bank-Marketing-Decision-Tree
 ┣ 📜 Task03_Bank_Marketing.ipynb
 ┣ 📜 bank-full.csv
 ┗ 📜 images
 ┗ 📜 README.md

## ✅ Conclusion
The Decision Tree model provides a clear and interpretable approach to predicting customer subscription. It highlights key factors influencing decisions and can help businesses optimize their marketing strategies.

---

