# Disaster-Related-Tweet-Classification-Using-NLP

# Overview
This project classifies tweets into disaster-related and non-disaster-related categories using Natural Language Processing (NLP). It applies machine learning models to extract meaningful insights from social media data, helping disaster response teams quickly identify relevant information.

# Tech Stack
1. Python – Main programming language
2. NLP Techniques – Tokenization, text cleaning, feature extraction
3. Embedding Models – TF-IDF, CBOW, BERT
4. Machine Learning Models – Logistic Regression, SVM, Decision Trees

# Working
1. Data Preprocessing:
   -> Clean and normalize tweets (remove URLs, punctuation, special characters).
   -> Tokenize text and handle missing values.

2. Feature Extraction:
   -> Use TF-IDF for term importance, CBOW for context-based embeddings, and BERT for deep semantic understanding.

3. Model Training & Evaluation:
   -> Train classifiers (Logistic Regression, SVM, Decision Trees, Random Forest) on extracted features.
   -> Evaluate models using Precision, Recall, F1-score, and Accuracy.

# Results & Insights
BERT & SVM achieved the highest F1-score (~78%), showing strong classification accuracy.
TF-IDF & Logistic Regression performed well (~75%), making it an efficient choice for simpler implementations.
CBOW embeddings showed potential but underperformed compared to BERT.

# Future Enhancements
1. Fine-tune BERT for specific disaster types (earthquakes, floods, wildfires).
2. Handle multilingual tweets for global disaster response.
3. Deploy as a real-time API for emergency services.

