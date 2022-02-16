# NLP-Classification-Sentiment-Analysis

## Overview
- **Business Need:** Improving services and customers satisfy for Bacchanal Buffet.
- **Solution:** Using Yelp data, Analyse Reviews, Customer’s Sentiment and provide suggestions
- **Objectives:** NLP Supervised Classification on Yelp Dataset, Sentiment Analysis on Yelp Dataset

## Tools
![image](https://user-images.githubusercontent.com/87232397/154207381-eed2ffcd-90e5-416d-9456-c86b6ae1a5d6.png)

## Methodology
![image](https://user-images.githubusercontent.com/87232397/154207763-87b4bbef-3d6c-4866-88d0-ef63d0d8b6f5.png)

## Text Processing
- **Adding Sentiment Features**
  - 1,2 —> Negative
  - 3 —> Neutral
  - 4,5 —> Positive
- **Removing Characters**
  - numbers (1-9) 
  - punctuation () 
  - new line (\n) 
  - Convert Lower Cas
- **Detecting Language**
  - Removing non English
- **Applying Stemming & Lemmatisation**

## Modelling
- **Split dataset into X (feature) and y (target)** 
- **Split dataset into training and test sets** 
- **Methods** 
  - Count Vectorizer, 10374 rows x 15082 features 
  - Count Vectorizer, Ngram,10374 rows x 244175 features 
  - TF-IDF 
  - TF-IDF, Ngram 
- **Classifier** 
   - LogisticRegression(), 
   - KNeighborsClassifier(), 
   - DecisionTreeClassifier(), 
   - RandomForestClassifier(), 
   - AdaBoostClassifier(), 
   - GradientBoostingClassifier(), 
   - MultinomialNB(), 
   - BernoulliNB() 

## Sentiment Analysis - Text Processing
- **Calculating Polarity, Subjectivity** 
  - TextBlob(text).sentiment
- **Calculating Pos, Neg, Neu, Compound** 
  - SentimentIntensityAnalyzer().polarity_scores()
- **Word Cloud**
