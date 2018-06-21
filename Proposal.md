## Overview

Problem Overview: Predicting Fluctuations in cryptocurrency transactions based on sentiment analysis of individual’s perception shared on social networking platforms. 



The problem statement is related to one of the trending topics - cryptocurrency and how it’s popularity spread in global world. The sudden volatility in its price very well captures the correlation between the sentiment of people and its effect over the price. We always assumed that stock market is governed by sentiment but couldn’t locate it with mathematical model. Sentiment analysis, geo-political  news can now be correlated with cryptocurrency's price as its effect has become transparent due to higher penetration of social media in the life of people where they exchanges their thoughts and perceptions.

## Data

We will be using user data from Twitter or Facebook (or any other social networking platforms) through APIs depending upon availability of volumes of data. We will be retrieving time series data of cryptocurrency’s values using quandl package provided in python. We might face some issues in storing and manipulating time series data based upon the requirement but we can surely overcome it by going through some tutorials.

## Method

First we will perform sentiment analysis for online tweets and posts of users by tagging them into very positive, positive, neutral, negative and very negative by performing sentiment analysis. Based on the data of the cryptocurrency in same time bound as of the above posts, we will train the model to correlate the rise in value with positive values, decrease in value with negative sentiment and consolidated movement with neutral sentiment. Model will be trained using some supervised algorithm by using packages like sklearn, scikit learn, numpy etc. We are planning to implement entire code of data collecting, cleaning, preprocessing, training the model, testing the model and fine tuning various parameters as per the output.

## Related Work

Algorithmic Trading of Cryptocurrency Based on Twitter Sentiment Analysis - Stuart Colianni, Stephanie Rosales, and Michael Signorotti - http://cs229.stanford.edu/proj2015/029_report.pdf



Rapid Prototyping of a Text Mining Application for Cryptocurrency Market Intelligence - https://arxiv.org/ftp/arxiv/papers/1611/1611.00315.pdf



Predicting Fluctuations in Cryptocurrency Transactions Based on User Comments and Replies - http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0161197



From Bitcoin to BigCoin - The Impact of Social Media on Bitcoin Performance - http://www.fmaconferences.org/Orlando/Papers/Bitcoin_FMA.pdf



Nowcasting the Bitoin Market with Twitter Signals - 

https://arxiv.org/pdf/1406.7577v3.pdf

## Evaluation

Performance will be captured by deriving a metric of price fluctuation w.r.t global sentiment. We will also try to prepare a confusion matrix which can easily show the relation between our predicted and actual values. We will also try to run Granger causality test for forecasting one time series data based on another time series data. Data will be plotted in terms of time series data for both attributes based on z score value which standardizes the value. 

