# Fake News Detection Engine

The project preprocesses a data set of news articles -- each predetermined to either be fake or real, by applying the Term Frequency - Inverse Document Frequency (TF-IDF) analysis. Afterwards, a Passive Aggressive Classifier is fitted with the training data to be used as a model for the test data. Currently, the accuracy of the model based on the data set provided is approximately 93%, although the number fluctuates by +/- 0.5%. 

The model was tested against 3 separate and random articles found online -- 2 of which are considered real articles from reputable sources, and the other a satirical article to be used as a fake. The model accurately spotted the fake news article; for the real articles, 1 was accurately spotted and the other gave a false negative result, unless CNN has some fake news articles.  

Although I only performed 3 random tests, I have doubts that the 93% accuracy rating is inaccurate. To make the model more realistic, I am currently working on not only cleaning my data set further, but also checking for any hints of data leakage.
