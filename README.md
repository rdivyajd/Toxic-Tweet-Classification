# Toxic-Comment-Classification
Toxic Comment Classification - on twitter data related to bullying
*Related to [Kaggle] competition*

| Author: Divya Rajendran

## Pre-Requisites / Requirements
Python3 is needed to run this code efficiently
### Required Packages
```bash
pip install jupyter numpy pandas seaborn matplotlib preprocessor string re nltk contractions collections wordcloud sklearn
```
Run this piece of code in terminal or cmd prompt, this will install all the required packages needed to run the jupyter notebook.

## Data
For the test data, tweets relate to a few hashtags like #metoo, #dontcoveritup, #youknew, #lonely, #alone, #WhyIStayed”, #bodyshamming, #YouOKSis, #EverydaySexism has been collected using twitter API and by making use of Jefferson-Henrique/GetOldTweets-python project code for test data

1. *The train data can be downloaded from the data page in the [Kaggle] competition.*

2. *The data has been obtained for the time line starting 01-Jan-2017 to 31-Mar-2018, 1000 tweets each day containing the nine hashtags*

## Model

A logistic regression model is trained on train data and the used it to predict probabilities of tweets falling into six class labels like - toxic, severe toxic, identity hate, threat, insult, and obscene is predicted.

## Conclusion & Results
Identifying abuse from tweets is a difficult process as readily labelled tweets are not available and the manual labelling is a tiresome and time consuming process. The logistic regression model achieved an accuracy of 98.6% on the train data. It would have been great if the test data had some pre-labelled tweets to get the accuracy of predictions. It would be better to to include feature extraction based on other details of the tweet like origin, time of the tweet and employ different models for better model to filter abusive tweets. 

[Kaggle]: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge
