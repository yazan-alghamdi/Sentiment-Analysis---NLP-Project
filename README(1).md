# Tourism Reviews Sentiment Analysis using Machine Learning

> A Natural Language Processing (NLP) project that classifies tourism
> reviews into positive and negative sentiments using TF-IDF feature
> extraction and multiple Machine Learning models.

------------------------------------------------------------------------

## Overview

This project implements a complete Natural Language Processing (NLP)
pipeline for sentiment analysis on tourism reviews collected from
various cultural and heritage destinations in Saudi Arabia.

The workflow covers data preparation, sentiment labeling, text
vectorization, model training, evaluation, and visualization. Multiple
machine learning algorithms are compared to identify the most effective
approach for classifying visitor opinions.

------------------------------------------------------------------------

## Project Objectives

-   Analyze tourism reviews using Natural Language Processing.
-   Automatically classify visitor opinions into positive and negative
    sentiments.
-   Compare different Machine Learning classifiers.
-   Evaluate model performance using standard classification metrics.
-   Visualize sentiment distribution across tourism destinations.

------------------------------------------------------------------------

## Dataset

The dataset contains textual reviews collected from multiple tourist and
heritage attractions across Saudi Arabia.

### Data Includes

-   Review Text
-   Rating
-   Tourist Location
-   Sentiment Label

  Rating       Label
  ------------ ----------
  1--2 Stars   Negative
  3--5 Stars   Positive

------------------------------------------------------------------------

## NLP Pipeline

``` text
Raw Reviews
      │
      ▼
Data Cleaning
      │
      ▼
Text Normalization
      │
      ▼
Sentiment Labeling
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Model Training
      │
      ▼
Performance Evaluation
      │
      ▼
Visualization
```

------------------------------------------------------------------------

## Data Preprocessing

-   Remove missing and duplicate reviews
-   Clean and normalize text
-   Generate sentiment labels
-   Prepare data for feature extraction

------------------------------------------------------------------------

## Feature Engineering

TF-IDF (Term Frequency--Inverse Document Frequency) with unigram and
bigram features was used to transform textual reviews into numerical
vectors for machine learning.

------------------------------------------------------------------------

## Machine Learning Models

  Model                     Purpose
  ------------------------- ---------------------------------------------------
  Logistic Regression       Linear baseline classifier
  Multinomial Naive Bayes   Probabilistic text classifier
  LinearSVC                 Margin-based classifier for high-dimensional text

------------------------------------------------------------------------

## Model Evaluation

The models were evaluated using:

-   Accuracy
-   Macro F1-Score
-   Classification Report
-   Confusion Matrix

------------------------------------------------------------------------

## Technologies Used

  -----------------------------------------------------------------------
  Category                      Technologies
  ----------------------------- -----------------------------------------
  Programming                   Python

  NLP                           Scikit-learn

  Feature Engineering           TF-IDF

  Machine Learning              Logistic Regression, Multinomial Naive
                                Bayes, LinearSVC

  Data Analysis                 Pandas, NumPy

  Visualization                 Matplotlib
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## Repository Structure

``` text
Tourism-Reviews-Sentiment-Analysis/
│
├── Dataset/
├── Notebook/
├── Results/
├── Figures/
├── Report/
└── README.md
```

------------------------------------------------------------------------

## Future Improvements

-   Multi-class sentiment classification
-   Transformer-based language models
-   Larger tourism datasets
-   Web deployment
-   Interactive dashboard

------------------------------------------------------------------------

## Author

**Yazan Ibrahim Al-Ghamdi**

Data Science Graduate --- Umm Al-Qura University

------------------------------------------------------------------------

> Developed as part of the Natural Language Processing course to
> demonstrate Machine Learning techniques for sentiment analysis of
> tourism reviews.
