# Disaster_tweets
Project Requirements
1. Goal: You are predicting whether a given tweet is about a real disaster or not. If so, predict 
a 1. If not, predict a 0.
2. Data: This only contains one file: tweets
 id - a unique identifier for each tweet
 text - the text of the tweet
 location - the location the tweet was sent from (may be blank)
 keyword - a particular keyword from the tweet (may be blank)
 target - this denotes whether a tweet is about a real disaster (1) or not (0)
3. Requirements: Please extract features in the dataset and/or create new features via 
text mining or even network modeling to predict the probability that a given tweet 
whether contains a real disaster or not.
a. Your approach should achieve a high accuracy or AUC (https://scikit-
learn.org/stable/modules/generated/sklearn.metrics.roc_auc_score.html), at 
least above 0.85. The higher the better
b. To achieve the above score, you must perform properly the following: EDA 
(exploratory data analysis), feature engineering, feature selection, model 
selection
c. You can also leverage existing any disaster keywork vocabularies. However, 
using existing package or API specialized for disaster detection is prohibited. 
NOT ALLOWED.
d. Please RANDOMLY split the tweets into 90% for training and 10% for testing 
or 80% for training/10% for validation/10% for testing. You must have code 
for random data splitting. Please perform 10 times randomly data splitting and 
for each splitting, you run you run your model, then get the average result of 
the above 10 runs.
