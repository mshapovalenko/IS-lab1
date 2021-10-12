# IS-Lab1 (EN)
Intelligent systems. Task for the laboratory for Perceptron training.
# Aim
Learn to write training (parameter estimation) algorithm for simple linear classifier.
# Tasks (maximum 8 points)
1. Create a program for classification using single Perceptron of two different objects into two classes according to two estimated features. Output estimation should be done acording to the following equation:
y = 1, if x1\*w1 + x2\*w2 + b > 0; y = -1, if x1\*w1 + x2\*w2 + b <= 0; here w1, w2 and b are the parameters, which should be initialized randomly and updated (estimated) later, using training algorithm; x1 and x2 are the object features, estimated using functions written in Matlab (available in Matlab code template or in Data.txt).
2. Write a training algorithm for created classifier. Use this parameter update formula:
w1(n+1) = w1(n) + eta\*e(n)\*x1(n); here 0 < eta < 1; e(n) = d(n) - y(n); - an error, estimated by comparing the desired output d(n) and the output, currently (for current example) received from the Perceptron.
w2(n+1) = w2(n) + eta\*e(n)\*x2(n);
b(n+1) = b(n) + eta\*e(n);
# Additional task (2 additional points)
Solve this classification task using Naive Bayes Classifier.
Some examples and tutorials for additional task:
- http://www.statsoft.com/textbook/naive-bayes-classifier
- https://en.wikipedia.org/wiki/Naive_Bayes_classifier
# Suggested reading
- Neural Networks and Learning Machines (3rd Edition), page 54, Table 1.1. 

Laboratory work code is in lab1.m
