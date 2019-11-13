# Quora-Insincere-Questions-Classification
## Problem Description
An existential problem for any major website today is how to handle toxic and divisive content. Quora wants to tackle the problem head-on to keep their platform a place where users can feel safe sharing their knowledge with the world.
Quora is a platform that empowers people to learn from each other. On Quora, people can ask questions and connect with others who contribute unique insights and quality answers. A key challenge is to weed out insincere questions -- those founded upon false premises, or that intend to make a statement rather than look for helpful answers. In the Case Study, a model is developed that identify and flag insincere questions to detect toxic and misleading content.

## Data Set Details
The dataset is collected from Kaggle and it consists of two files in CSV (Comma Separated Values) format namely train.csv and test.csv for training and testing purpose respectively. The dimension of training data is 1.31m * 3 and testing data is 376k * 2 (total 6GB of data). The three columns in training data are:
•	.qid : Unique Question Identifier
•	.question_text : Quora Question Text
•	.target : a question labelled “insincere” has a value of 1, otherwise 0
