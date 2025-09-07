K-Means Clustering Algorithm


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/todkarsant/Machine_learning/blob/Main/Clustering/KMeans_Clustering.ipynb)


# K-Means Clustering Algorithm

K-Means is a popular unsupervised machine learning algorithm used for partitioning a dataset into *k* distinct, non-overlapping subgroups (clusters). The goal of K-Means is to group data points such that the sum of squared distances between data points and their assigned cluster centroid is minimized.

## How it Works:

1.  **Initialization:** Choose the number of clusters, *k*. Randomly select *k* data points from the dataset as the initial cluster centroids.
2.  **Assignment:** Assign each data point to the nearest centroid. The distance is typically measured using Euclidean distance.
3.  **Update:** Recalculate the centroids for each cluster by taking the mean of all data points assigned to that cluster.
4.  **Iteration:** Repeat steps 2 and 3 until the centroids no longer change significantly or a predefined number of iterations is reached. This indicates that the clusters have stabilized.

## Key Concepts:

*   **Centroid:** The center of a cluster, calculated as the mean of all data points belonging to that cluster.
*   **Inertia (Within-Cluster Sum of Squares):** The sum of squared distances between each data point and its assigned centroid. K-Means aims to minimize inertia.
*   **Elbow Method:** A common technique used to determine the optimal number of clusters (*k*). It involves plotting the inertia for different values of *k* and looking for an "elbow" point where the rate of decrease in inertia slows down.

## Advantages of K-Means:

*   **Simplicity:** It is relatively easy to understand and implement.
*   **Efficiency:** It is computationally efficient, especially for large datasets.

## Disadvantages of K-Means:

*   **Requires specifying *k*:** The number of clusters needs to be determined beforehand, which can be challenging.
*   **Sensitive to initial centroids:** The final clustering results can be influenced by the initial choice of centroids.
*   **Sensitive to outliers:** Outliers can significantly affect the centroid calculations.
*   **Assumes spherical clusters:** K-Means works best when the clusters are roughly spherical and equally sized.

## Applications:

K-Means is widely used in various applications, including:

*   Customer segmentation
*   Image compression
*   Document analysis
*   Anomaly detection
*   Recommendation systems
