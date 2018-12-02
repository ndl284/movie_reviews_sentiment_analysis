# Movie Reviews Sentiment Analysis

##### This project just covers a natural language processing, classification problem. Where the network needs to
##### train on and evaluate phrases in a movie review data set and classify them on a varying degree of negativity and
##### positivity e.g. very positive, mildly positive, neurtral etc.

##### The data set used for this is a rotten tomatoes dataset that I found on Kaggle (Link provided below.)
###### Kaggle Competition: https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews

## What I did?
##### I just performed a little data processing before passing it through an embedding layer and training it on 
##### two layers of LSTMs and a subsequent dense layers. Implemented the network using Keras and used pandas, numpy 
##### and nltk to process the text data, used matplotlib just to plot the accuracies and loss.

## Result.
##### Submitted the predictions from the test data set to Kaggle and got a score of 64%.
