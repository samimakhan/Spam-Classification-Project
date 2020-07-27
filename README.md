# spam-classifier
Spam Classifier built using CountVectorizer and Tf-idf Vectorizer. 
Source of dataset: https://www.kaggle.com/uciml/sms-spam-collection-dataset
We employed Upsampling and Cross-val in our project, and built the following models:
* Naive Bayes model with imbalanced dataset, using CountVectorizer
* Naive Bayes model with imbalanced dataset, using Tf-idf Vectorizer
* Naive Bayes model with cross-validation, using CountVectorizer
* Naive Bayes model with cross-validation, using Tf-idf Vectorizer
* Decision Tree models wirth imbalanced dataset, cross-val, and upsampled data.

For EDA, we created the following:
* Histogram of most commonly occuring words in the ham and spam messages
* Wordclouds of most commonly occurring words in the ham and spam messages
* Bar chart showing the number of spam and ham messages

We reported the f-measure and accuracy scores of each model as part of our findings in our powerpoint presentation, which is uploaded as well. 

