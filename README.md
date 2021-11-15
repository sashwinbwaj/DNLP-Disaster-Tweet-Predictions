# DNLP-Disaster-Tweet-Predictions
This project uses NLP to clean ~10000 tweets and encode it using various vectorizers such as Count/Tf-Idf &amp; Hashing. The encoded matrix is used to predict if the tweet is about a disaster, using multiple classifiers. A ridge regression classifier is taken as a benchmark, resulting is ~80% accuracy. Naive Bayes classifier, one of the most popular algorithms used in NLP was also implemented with hyper-parameter tuning, resulting in enhanced accuracies in both the K-folds validation set &amp; out-of-sample test set.
