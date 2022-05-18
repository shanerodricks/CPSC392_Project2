# CPSC392_Project2
Using the dataset krispykreme.csv,
a) make 3 scatterplots using ggplot to show:
Sodium_100g vs Total_Fat_100g
Sodium_100g vs. Sugar_100g
Sugar_100g vs Total_Fat_100g
You will be graded on the effectiveness of the graphs as well as their content.
b) Using the scatterplots from part a as well as the donuts dataset, thouroughly discuss which clustering method (KMeans, Gaussian Mixture Models (EM), Hierarchical Clustering, or DBSCAN) you think would be best for this data and WHY. Be sure to include discussions of assumptions each algorithm does/does not make, and what types of data they are good/bad for (mention each of the 4 algorithms at least once) and how they apply to this specific dataset. (IN A MARKDOWN CELL)
you should be making statements that both 1) discuss characteristics of the algorithm and 2) specifically discuss how that characteristic applies (or doesn't) to this dataset.
Please note that for this assignment, "It's easier to code" does not count as a valid reason. The reasons should be based on the algorithms/data.
(You must use "**" to make any mention of one of the algorithms bold in your discussion. For example "I think **DBSCAN** is the best algorithm ever!" will make the word "DBSCAN" bold in a Markdown cell).
c) Implement the TWO algorithms you think will work BEST (1 algo) and WORST (1 algo) here using all 3 variables Sodium_100g, Total_Fat_100g and Sugar_100g, and describe how you chose any hyperparameters (such as distance, # of clusters, min_samples, eps, linkage...etc). Make sure to z-score your variables. (IN A MARKDOWN CELL)
d) Thouroughly discuss the performance of your clustering models. For each algorithm (best and worst):
which metric did you use to asses your model? (IN A MARKDOWN CELL)
how did your model perform? (IN A MARKDOWN CELL)
remake the 3 graphs from part a, but color by cluster assignment. Describe what characterizes each cluster, and give an example of a label for that cluster (e.g. "these donuts are low fat, and low sugar so I would call these healthy donuts") (IN A MARKDOWN CELL)
e) Choose ONE other of the _100g variables from the data set to add to your clustering model to improve it.
explain why you chose this variable. Either based on improvement in metrics, or outside knowledge you have about food/donuts (IN A MARKDOWN CELL)
make a new model, identical to the model you thought would be best in part c, but also including your new variable.
did this variable improve the fit of your clustering model? How can you tell? (IN A MARKDOWN CELL)
