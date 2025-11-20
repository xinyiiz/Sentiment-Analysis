# Sentiment-Analysis
This project builds a sentiment analysis model that predicts the review score of Google Play Store app reviews. Each team member collects review data for a different app, preprocesses it, trains an individual deep learning model, and evaluates it across all team datasets.


This repository contains both the Group notebook and Individual notebook for Assignment 2 of the Deep Learning module. The task focuses on building, training, evaluating, and comparing sentiment-analysis models on Google Play Store reviews.

📂 Repository Structure
├── ASG_Problem 2_Group 1.ipynb       # Group notebook (shared workflow)
├── ASG_Problem2_Tan Xin Yi.ipynb     # Individual notebook (personal model)
└── README.md


---

## 🧠 Project Overview

The goal of this assignment is to develop a **deep learning model** that predicts sentiment from Google Play Store app reviews.

Each student:
- Chooses a unique app  
- Scrapes review text + rating  
- Cleans and preprocesses the data  
- Builds a deep learning sentiment classifier  
- Evaluates on personal + group datasets  

The **group notebook** consolidates shared preprocessing and evaluation.

---

## 📓 Notebook Descriptions

### 1️⃣ ASG_Problem 2_Group 1.ipynb  
**Purpose:**  
Handles the shared steps across the group.

**Includes:**
- Group dataset loading  
- Text cleaning & preprocessing  
- Tokenization & padding  
- Tensor conversion  
- Group evaluation workflow  
- Comparison of all individual models  
- Final group sentiment classifier pipeline  

---

### 2️⃣ ASG_Problem2_Tan Xin Yi.ipynb  
**Purpose:**  
Your personal assignment notebook.

**Includes:**
- Individual dataset collection  
- NLP preprocessing steps  
- Deep learning model (Embedding + LSTM/GRU/Conv1D)  
- Training curves (loss, accuracy)  
- Model evaluation on all group datasets  
- Summary of findings  

---

## 🔄 Workflow Summary

### **1. Data Collection**
- Scraped reviews with `google_play_scraper`
- Extracted `content` and `score`
- Saved in CSV or JSON format

### **2. Preprocessing**
- Lowercasing  
- Removing punctuation, symbols, URLs  
- Tokenization  
- Padding  
- Train-test split (80/20)

### **3. Model Development**
Models typically include:
- Embedding layer  
- LSTM / GRU / Conv1D  
- Dense layers  
- Softmax output  

### **4. Evaluation**
- Accuracy  
- Loss curves  
- Optional confusion matrix  
- Cross-testing across all group datasets

### **5. Group Final Model**
Best individual model is used for:
- cross-evaluation
- a final group decision for best model
  
## How It Works
User Input → Preprocess → Model → Sentiment Emoji

Example Output:
🙂 Positive
😐 Neutral
☹️ Negative


---

## 📚 Dependencies

Install the required packages:
pip install tensorflow keras pandas numpy scikit-learn matplotlib nltk google-play-scraper

---

## 👥 Team Information

**Group 1**  
- Tan Xin Yi
- Cheong Wei En
- Pang Ai Jie Jennie 
- Ilamurugu Subramanian Harini 
- Alluru Rishitha Reddy 

---

Run all cells in order to reproduce:
- data preparation  
- model training  
- evaluation  
- sentiment predictions  

---

## ✅ Summary

This repository contains both the group and individual components of Assignment 2.  
It demonstrates a full NLP workflow: data scraping, preprocessing, model development, cross-evaluation, and final sentiment prediction.

