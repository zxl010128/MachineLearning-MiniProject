# MachineLearning-MiniProject

## Motivation
Imagine that you have been hired as a Data Scientist by Amazon, and your first task is to evaluate customer sentiment towards their products. Many online stores selling Amazon products provide their customers with an option to leave a review, but they might not have a rating system, or the customers might choose to leave a review without rating. However, you still want to use these reviews in your report. Thus, you need to develop a reliable model that can automatically assign setiment given a review.

To develop your model, you have been given a collection of customer reviews on products like Alexa Echo, Echo dots, Alexa Firesticks etc. with their corresponding ratings. The ratings vary from 1 to 5, but to simplify the problem, you will consider reviews with ratings 1 & 2 to have negative sentiment, with 3 having neutral sentiment, and 4 & 5 having positive sentiment.

## Brief Intro
This data analysis project has been done during the UNSW summer school COMP3411 in January 2021. After importing data and pre-processing data, I created a training set and a test set. After that, I evaluated the performance of three classifiers - Decision Tree (DT), Multinomial Naive Bayes (MNB), and Artificial Neural Networks (ANN).　

In part5, I did several extra works in order to improve the accuracy of the model. I did 2 more pre-processing methods(stopwords remove and tokenization), modified the test_size and shuffle situation, and modified the alpha value for the classifier. The overall accuracy increased from 0.86 to 0.91. It still can be improved.　

Please note that any copying behaviors and inappropriate paraphrasing might cause misconduct or undermine academic integrity by your institution. All rights reserved by Xinlei Zhang.
