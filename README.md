# Credit-Card-Fraud-Detection

In this project, I use a dataset of nearly 28,500 credit card transactions and multiple unsupervised anomaly detection algorithms, I am going to identify transactions with a high probability of being credit card fraud. In this project, I will build and deploy the following two machine learning algorithms:

Local Outlier Factor (LOF)
Isolation Forest Algorithm
Furthermore, using metrics suchs as precision, recall, and F1-scores, I will investigate why the classification accuracy for these algorithms can be misleading.

In addition, I will explore the use of data visualization techniques common in data science, such as parameter histograms and correlation matrices, to gain a better understanding of the underlying distribution of data in our data set.

Local Outlier Factor (LOF)

The anomaly score of each sample is called Local Outlier Factor. It measures the local deviation of density of a given sample with respect to its neighbors. It is local in that the anomaly score depends on how isolated the object is with respect to the surrounding neighborhood.

Isolation Forest Algorithm

The IsolationForest ‘isolates’ observations by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature.

Since recursive partitioning can be represented by a tree structure, the number of splittings required to isolate a sample is equivalent to the path length from the root node to the terminating node.

This path length, averaged over a forest of such random trees, is a measure of normality and our decision function.

Random partitioning produces noticeably shorter paths for anomalies. Hence, when a forest of random trees collectively produce shorter path lengths for particular samples, they are highly likely to be anomalies.
