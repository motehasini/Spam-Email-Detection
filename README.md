# Spam Email Detection using Naive Bayes

## Synent Technologies Internship - Task 8

---

# Project Overview

This project detects spam emails using Natural Language Processing (NLP) and the Naive Bayes Machine Learning algorithm.

The objective of this project is to classify messages into:

- Spam
- Ham (Not Spam)

The project demonstrates practical NLP, text preprocessing, Machine Learning classification, and spam filtering techniques.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- NLTK

---

# Dataset Information

Dataset Used:
SMS Spam Collection Dataset

The dataset contains:

- Message text
- Message labels (spam or ham)

---

# Features and Analysis Performed

## Data Cleaning

- Selected important columns
- Renamed columns
- Checked missing values
- Removed duplicate records

## Exploratory Data Analysis (EDA)

- Spam vs ham distribution
- Message length analysis
- Message length comparison

## Natural Language Processing (NLP)

- Text vectorization using CountVectorizer
- Conversion of text into numerical features

## Machine Learning

- Train-test split
- Naive Bayes classifier training
- Spam prediction

## Model Evaluation

- Accuracy score
- Confusion matrix
- Classification report

## Word Analysis

- Common word analysis
- Spam word identification

## Sample Predictions

- Tested model using sample messages

---

# Visualizations Included

- Count Plots
- Histograms
- Boxplots
- Heatmaps

---

# Machine Learning Algorithm Used

## Naive Bayes Classifier

Naive Bayes is a classification algorithm commonly used for text classification problems such as spam detection.

In this project:

- Text messages were converted into numerical vectors.
- The model learned patterns from spam and ham messages.
- The trained model classified new messages as spam or ham.

---

# NLP Technique Used

## CountVectorizer

CountVectorizer converts text messages into numerical vectors based on word frequency.

This allows Machine Learning algorithms to process textual data.

---

# Model Evaluation Metrics

## Accuracy Score

Measures overall prediction accuracy.

## Confusion Matrix

Shows correct and incorrect classifications.

## Classification Report

Provides:

- Precision
- Recall
- F1-Score

---

# Key Insights

1. Spam messages often contain promotional or urgent words.

2. Spam messages are generally longer than normal messages.

3. Naive Bayes performs effectively for text classification.

4. NLP techniques help automate spam filtering systems.

5. Machine Learning successfully classifies spam and ham messages.

---

# Files Included

```text
Task-8-Spam-Email-Detection/
│
├── task8.ipynb
├── spam.csv
├── README.md
```

---

# How to Run the Project

## Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
```

## Open Jupyter Notebook

```bash
jupyter notebook
```

## Run the Notebook

Open:

```text
task8.ipynb
```

Run all cells sequentially.

---

# Conclusion

This project successfully implemented a Spam Email Detection system using Natural Language Processing and Machine Learning classification techniques.

The project demonstrated practical skills in:

- NLP
- Text preprocessing
- Feature extraction
- Machine Learning
- Classification evaluation

---

# Author

Mote Hasini
