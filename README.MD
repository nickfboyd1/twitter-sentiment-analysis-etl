## Overview
The goal of this post is to demonstrate how to use Twitter's API & Python's primary natural-language processing (NLP) libraries to easily analyze the overall sentiment of recent tweets on any given subject.

Additionally, I'll show how to load this data into a SQL database or S3 bucket on AWS. This type of ETL or data pipeline would likely be necessary in the case that I wanted to continously maintain and analyze a larger list of tweets over time, or in a professional setting where multiple analysts and engineers need to access to the data.

The following topics are covered:

- Extracting tweets from the Twitter API using a Python library called Tweepy
- Transforming the tweets data into a pandas dataframe for ease of analysis
- Cleaning and pre-processing unstructured, unlabeled text data
- Loading the cleaned, tweet dataframe into a SQL database or Amazon S3 bucket.
- Executing sentiment analysis using libraries like scikit-learn and transformers
