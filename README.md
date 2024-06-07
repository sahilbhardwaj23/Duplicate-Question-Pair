# Duplicate Question Pair Checker
This project aims to identify duplicate question pairs using NLP techniques and machine learning models. The dataset used for this project is the Quora Question Pairs dataset, which was originally provided as part of a Kaggle competition.

## Introduction
Duplicate questions can clutter forums and make information retrieval difficult. This project uses Natural Language Processing (NLP) and machine learning techniques to determine if two questions are semantically equivalent. This can help in reducing redundancy and improving the user experience on Q&A platforms like Quora.

## Dataset
The dataset used is the Quora Question Pairs dataset provided by Quora for a Kaggle competition. It contains pairs of questions with labels indicating whether the questions are duplicates.

## Technologies Used
* Natural Language Processing (NLP)
*  Bag of Words (BOW)
*  Machine Learning
*  Random Forest Classifier
*  XGBoost Classifier

## How It Works
*  Input: Provide a pair of questions.
*  Processing: The questions are processed using NLP techniques to transform text into numerical features.
*  Prediction: The processed features are fed into machine learning models (Random Forest and XGBoost) to predict whether the questions are duplicates.
*  Output: The model outputs whether the question pair is a duplicate or not.
