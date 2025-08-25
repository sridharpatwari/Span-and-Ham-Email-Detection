# 📧 Spam-and-Ham-Detection using Machine Learning

## 📌 Project Overview
This project focuses on classifying emails as *Spam* or *Ham (Not Spam)* using machine learning.  
The goal is to build a reliable model that can filter out unwanted spam emails and improve the efficiency of email systems.

---

## 📊 Dataset
- The dataset used contains *labeled email messages* with two categories:
  - *Spam* → Unwanted promotional / malicious messages  
  - *Ham* → Legitimate emails  
- Dataset was preprocessed to remove unwanted characters, stopwords, and perform text normalization.

---

## ⚙ Steps Involved
1. *Data Preprocessing*
   - Converted text into lowercase
   - Removed punctuation & stopwords
   - Tokenized text
   - Applied *TF-IDF Vectorization* to convert text into numerical format

2. *Model Training*
   - Implemented :
     - *Logistic Regression*

3. *Model Evaluation*
   - Evaluated using:
     - *Accuracy*
     - *Precision*
     - *Recall*
     - *F1-Score*
   - Chose the best-performing model for deployment

---

## 📈 Results
- The trained model successfully achieved *high accuracy* in distinguishing Spam and Ham messages.
- Performance metrics confirmed the robustness of the chosen algorithm (Naive Bayes and Logistic Regression performed best).

## 📊 Output

Here are some sample outputs from the Spam-Ham Detection model:

### 1. DashBoard  
![Dashboard Preview](https://github.com/sridharpatwari/Span-and-Ham-Email-Detection/blob/main/Images/Dashboard.png)

### 2. Spam Email Prediction  
![Spam Email](https://github.com/sridharpatwari/Span-and-Ham-Email-Detection/blob/main/Images/Spam_output.png)

### 3. Ham Email Prediction  
![Ham Email](https://github.com/sridharpatwari/Span-and-Ham-Email-Detection/blob/main/Images/Ham_output.png)

### 4. Error Message 
![Error Prediction](https://github.com/sridharpatwari/Span-and-Ham-Email-Detection/blob/main/Images/Error_Message.png)


---

## 🚀 Technologies Used
- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📌 Future Work
- Deploy the model as a web application
- Enhance with deep learning (LSTM/Transformers for text classification)
- Train with larger, real-world email datasets

---

## 🏆 Conclusion
This project demonstrates how *Machine Learning can effectively detect spam emails*, reducing risks of phishing, scams, and unwanted promotional content.

---
