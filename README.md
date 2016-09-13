# Handwritten-Digit-Recognition
Machine Learning: Assignment deals with recognizing handwritten digits. 

**Problem Statemet:** In this problem we are working on **Handwritten Digit Recognition Data** but we are restricting our analysis to digit 2 and 3. Training data is retrieved from **zip.train** and test data is retrieved from **zip.test** dataset from the **ElemStatLearn** library. 

**Concepts:**

**1. knn:** k-nearest neighbour classification for test set from training set. For each row of the test set, the k nearest (in Euclidean distance) training set vectors are found, and the classification is decided by majority vote, with ties broken at random. If there are ties for the kth nearest vector, all candidates are included in the vote.


**2. 10 Fold cross validation:** A 10-fold CV is carried out as follows:

a. Randomly split the data into 10 equal sized subsamples

b. Fit the model using 9 out of 10 subsamples as training data and calculate the testing error using the remaining one.

c. Alternate the testing sample, and average the total of 10 experiments

