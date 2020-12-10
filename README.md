Project Purpose: 
The purpose of this project is to conduct sentiment analysis on handyman reviews in the Yelp Open Data Set. The sentiment analysis will be accomplished using
classification algorithims.

Key Associated Files:
- Final_Yelp_Sentiment_Analysis.ipynb
- Final_Yelp_Presentation.pptx

Approach:
The Yelp dataset had over 8 million observations. I was able to reduce it from 8 million observations to 7000 specific handyman observations.
I then seperated the reviews into two categories, Low ratings( 1 star and 2 star ratings) and High Ratings( 4 star and 5 star ratings). i conducted
an EDA using an N-Grams Analysis, Word Frequency Analysis, and NTLK Parts of Speech analysis. For the baseline model I used a Naive Bayes Classifier.
The Model Accuracy was .716. After looking at the dataset I saw that I was oversampling. So I reduced my positive observations to make it close to the amount
of negative observations. This improved the accuracy score to .910. I then trained an Extra Trees Classifier, Random Forest Classifier, and Gradient Boosting Classifier
on the dataset. The Naive Bayes Classifier performed the best in Accuracy, F1, Recall, and Precision.

Next Steps:
Adjust the hyperparameters to improve the metric scores of the models.
