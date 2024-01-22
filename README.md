A fruit breeding research station wants to investigate the possibility of utilising k-means clustering to understand data collected by the researchers. The fruit database contains a data set of 1,500 fruit blossoms from three different fruit types (apricots, peaches, and plums). The sepal length and width of fruit blossoms were measured on fruit trees between 7 and 10 years

Steps

1. Sense-check and normalise/standardise the data set to define k = ?
2. Determine the number of clusters (k) using, for example, the elbow method or the silhouette method.
3. Randomly select the cluster centroids.
4. Measure the distance between the data points and each centroid.
5. Assign each data point to the nearest centroid.
6. Recalculate centroids by calculating the mean value of all the samples assigned to that cluster.
7.  Repeat Steps 4 - 6 until no further change is observed in the centroids or the assignments of data points to clusters.
8. Once the clusters are stable, the process is complete. You can now evaluate the clustering and extract insights that address the original business problem.
