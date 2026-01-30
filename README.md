# SMS Spam Classifier

## 📌 Project Description
This project implements an SMS spam classification system using machine learning.  
The goal is to classify text messages as either **spam** or **not spam** (ham).  
It uses **CountVectorizer** for feature extraction and a **Multinomial Naive Bayes** classifier for training.

---

## 🛠 Skills Learned
- Text preprocessing  
- Feature extraction using CountVectorizer  
- Classification with Naive Bayes  
- Model evaluation (accuracy, precision, recall)

---

## 🔑 Steps in the Project
1. **Data Loading**: Import the `spam.csv` dataset containing SMS messages and labels.  
2. **Data Preprocessing**: Clean the dataset, rename columns, remove duplicates, and standardize labels.  
3. **Feature Extraction**: Convert text messages into numerical features using CountVectorizer.  
4. **Model Training**: Train a Multinomial Naive Bayes classifier on the processed data.  
5. **Model Evaluation**: Test the model on unseen data and measure accuracy (~98%).  
6. **Prediction**: Demonstrate classification on new, unseen messages.

---

## 🚀 How to Run
1. Open the notebook in **Google Colab**.  
2. Upload the dataset (`spam.csv`).  
3. Run all cells step by step.  
4. Try predicting with your own custom SMS messages.

---

## 🌍 Real-World Application
This project shows how machine learning can be applied to **spam detection** in communication systems, improving security and productivity by filtering unwanted messages.
