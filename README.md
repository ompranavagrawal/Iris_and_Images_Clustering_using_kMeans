**Objective**

The project aims to accurately cluster data using the K-Means algorithm, focusing on minimizing centroid distances to improve cluster quality.

**Preprocessing**

Data normalization and image smoothing techniques, including Gaussian smoothing, were employed to enhance clustering performance.

**Dimensionality Reduction**

Truncated SVD and t-SNE were used for reducing dimensions, alongside MinMaxScaler for feature scaling, to prepare data for clustering.

**K-Means Algorithm Application**

Initial centroids were chosen from data points to avoid bad initializations.

The Euclidean distance was used for assigning data points to the nearest centroid.

The process iterated until k centroids were determined, optimizing cluster quality.

**Observations**

Choosing centroids from data points yielded better results.

Optimal clustering for the Iris dataset was achieved with 3 clusters, as indicated by silhouette scores and inertia calculations.

For the Digits dataset, 10 clusters provided the best silhouette scores, indicating optimal clustering.

**Conclusion**

K-Means clustering effectively labeled the Iris and Digits datasets, demonstrating the algorithm's capability to manage and cluster large datasets efficiently.
