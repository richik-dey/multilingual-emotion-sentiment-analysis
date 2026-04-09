# Multilingual Emotion-Aware Sentiment Intelligence System for Temporal Analysis of Public Discourse

This project presents a multilingual emotion-aware sentiment intelligence system for analyzing public discourse related to the Russia–Ukraine conflict across different temporal phases. The system integrates sentiment classification, emotion detection, and engagement analysis to understand how public opinion evolves over time.

## Project Overview

- **Domain:** Natural Language Processing (NLP), Social Media Analytics, Multilingual Text Mining
- **Techniques:** Multilingual NLP, Sentiment Analysis, Emotion Detection, Temporal Analysis, Engagement Metrics Analysis
- **Machine Learning Models Used:** Linear Regression, Logistic Regression, Naive Bayes, SVM (Support Vector Machine), Decision Tree, Random Forest, KNN (K-Nearest Neighbor), XGBoost (Extreme Gradient Boosting)
- **Deep Learning Algorithms Used:** MLP (Multi-Layer Perceptron), CNN (Convolutional Neural Network), RNN (Recurrent Neural Network), LSTM (Long Short-Term Memory), Transformer, Hybrid (CNN + LSTM), GAN (Generative Adversarial Network), BERT (Bidirectional Encoder Representations from Transformers)
- **Sentiment Classes:** Positive, Negative, Neutral
- **Emotion Labels:** Anger, Fear, Joy, Sadness, Love, Surprise
- **Best Accuracy:** BERT - 91.91%

## Workflow

1. Collect multilingual Twitter dataset for early, mid, and later war phases
2. Perform text preprocessing (remove URLs, mentions, noise, stopwords)
3. Handle multilingual text normalization and encoding
4. Apply sentiment classification (VADER, XLM-RoBERTa)
5. Perform emotion detection using BERT-based models
6. Extract features using TF-IDF and Bag-of-Words
7. Train Machine Learning and Deep Learning models
8. Analyze engagement metrics (likes, retweets)
9. Perform temporal analysis across three phases
10. Apply statistical validation (Chi-Square and Cramér’s V)
11. Generate visualizations and comparative graphs

## Tools & Libraries

- Python (Google Colab)
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Transformers (Hugging Face)
- VADER Sentiment
- WordCloud
- Langdetect

## Dataset
https://www.kaggle.com/datasets/bwandowando/ukraine-russian-crisis-twitter-dataset-1-2-m-rows

## Team Member

**Richik Dey**    
B.Tech – Information Technology  
Kalinga Institute of Industrial Technology (KIIT-DU), Bhubaneswar, Odisha    
Project Type: Group  
Guide: Dr. Partha Sarathi Paul 

## License

This repository is for education and demonstration purposes only.
