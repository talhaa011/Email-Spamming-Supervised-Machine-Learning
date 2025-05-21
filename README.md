# 📧 Email Spam Detection Project

This project focuses on building a machine learning model to classify emails as **spam** or **ham (not spam)**. Accurate spam detection is essential for filtering malicious or irrelevant content from users' inboxes.

---

## 📝 Problem Statement

The goal is to build a classification system that can accurately predict whether an incoming email is spam. This helps in maintaining inbox hygiene and enhances the overall email experience by removing unwanted messages.

---

## 🎯 Objectives

- Load and explore the dataset  
- Preprocess the text data and convert it into numerical format  
- Train and evaluate multiple classification models (e.g., Naive Bayes, Random Forest)  
- Tune hyperparameters using `GridSearchCV`  
- Evaluate performance using metrics like **accuracy**, **precision**, **recall**, and **F1 score**  
- Identify and interpret the best-performing model  

---

## 🗃️ Dataset

The dataset used is [`spam.csv`](spam.csv), which contains two main columns:

- **Label**: Indicates whether the email is 'ham' or 'spam'  
- **Message**: The actual content of the email  

---

## 📊 Data Preprocessing Steps

- Checked and handled **null values**  
- **Dropped duplicates** to ensure clean training data  
- **Encoded** the categorical target (`ham`/`spam`) into numerical format (`0`/`1`)  
- Used **CountVectorizer** to transform textual data into numerical features  

---

## 📈 Exploratory Data Analysis

- Visualized message length distribution to identify trends  
- Plotted word frequency and spam vs ham distribution  
- Created bar plots and histograms to analyze data imbalance  

---

## 🤖 Model Building

Multiple models were trained and evaluated:

- **Naive Bayes Classifier**
- **Random Forest Classifier**
- Hyperparameter tuning using **GridSearchCV**

### Evaluation Metrics Used:

- Accuracy Score  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

---

## 🔮 Prediction

After training and tuning, the best-performing model (e.g., **Random Forest**) was used to make predictions on unseen data.

### ✅ Interpretation of Predictions:

- **Spam (Label: 1)**: The message is classified as spam  
- **Ham (Label: 0)**: The message is classified as not spam  

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---
## 📬 Contact

For any inquiries or collaboration, feel free to reach out:

- 📧 **Email**: muhammadtalha3589@gmail.com
- 💼 **LinkedIn**: https://www.linkedin.com/in/muhammad-talha-sial/
