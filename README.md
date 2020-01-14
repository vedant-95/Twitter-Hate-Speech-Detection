# Twitter-Hate-Speech-Detection
A repository

Our project analyzed a dataset CSV file from Kaggle containing 31,935 tweets. The dataset was heavily skewed with 93% of tweets or 29,695 tweets containing non-hate labeled Twitter data and 7% or 2,240 tweets containing hate-labeled Twitter data. 

1. The first step of building our model was to balance the number of hate and non-hate tweets. 
2. We clean the tweets by employing lemmatization, stemming, removal of stop words, and omissions. 
3. Then for the preprocessing step, we use Bag of words and Term Frequency Inverse Document Frequency (TFIDF). 
4. For both the Bag of words and TFIDF, we run 5 classification algorithms, namely Logistic Regression, Naive Bayes, Decision Tree, Random Forest and Gradient Boosting. 
5. These 5 algorithms are ran again after performing dimensionality reduction for both TF-IDF and Bag of Words.

The data cleaning.ipynb contains the code for cleaning the tweets.
Final working code.ipynb file contains the code for model building and visualisations.
