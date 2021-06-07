# News-articles-clustering

Problem Statement :

Dataset consists of news articles pertaining to business,political,entertainment, sports,technology are mentioned in JSON format. There is no segregation of articles in the dataset. All are mixed. We have to segregate the articles and validate which article pertains to which topic(business,political,entertainment, sports,technology ).


Solution:

1) To tackle this problem I have implemented the K-means clustering
2) Firstly, I applied the K-means clustering without dimensionality reduction
3) Secondly, I applied the K-means clustering with dimensionality reduction (Using PCA), which improves 
 performance of model by feature extraction.
4) In addition to that I found out  
     a) which cluster has max. articles(before & after implementing PCA)
     b) top 50 words in entertainment cluster and printing last 50th word (before & after implementing PCA)
     
Dependencies:

Python 3+,
jupyter notebbook,
Pandas,
Numpy,
Sklearn,
K-means,
PCA

Purpose:

The purpose of this project is to gain insights & help others in 
a) Pratical implementation - Clustering of News articles with the help of K-Means alogarithm for finding the suitable & related topics clusters
b) Dimensionality reduction using PCA.

