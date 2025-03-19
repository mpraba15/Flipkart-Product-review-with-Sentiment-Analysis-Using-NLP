## Project Overview: Flipkart Product Reviews Sentiment Analysis using NLP
This project focuses on analyzing Flipkart product reviews using Natural Language Processing (NLP) techniques to classify sentiment. 

### Introduction:
Flipkart is one of the most popular Indian companies.

India's biggest online store for Mobiles, Fashion (Clothes/Shoes), Electronics, Home Appliances, Books, Home, Furniture, Grocery, Jewelry, Sporting goods,...

It is an e-commerce platform that competes with popular e-commerce platforms like Flipkart.

One of the most popular use cases of data science is the task of sentiment analysis of product reviews sold on e-commerce platforms.

### Data Collection:

The dataset is loaded from a CSV file.

### Data Understanding:

The dataset is examined using .head(), .tail(), .info(), and .value_counts() functions.

Missing values are checked and handled.

### Data Cleaning:

Null values are removed.

Exploratory data analysis (EDA) includes sentiment distribution visualization using Seaborn.

### Text Preprocessing:

Tokenization and stopword removal using NLTK.

Stemming using PorterStemmer.

Feature extraction using CountVectorizer.

### Model Building:

The dataset is split into training and testing sets.

A Naïve Bayes classifier (MultinomialNB) is trained to classify reviews based on sentiment.

### Evaluation:

Model performance is assessed using accuracy score and classification report.
