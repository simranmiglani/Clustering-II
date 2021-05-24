# Clustering-II
Clustering algorithms seek to learn, from the properties of the data, an optimal division or discrete labeling of groups of points.
Our dataset is first clustered and then visualised, using KMeans and make_blobs.
Applied hierarchical clustering to cluster this dataset using AgglomerativeClustering and then generate the scatter plot of the clustering results.
Generated the dendrogram using dendrogram function and linkage function for the dataset.
Attempted to use k-means to try to identify similar digits without using the original label information.
In the end, I applied KMeans in color compression within images. In most images, a large number of the colors will be unused, and many of the pixels in the image will have similar or even identical colors. Now, the image with 16 million colors is reduced to just 16 colors, using a k-means clustering across the pixel space. The result is a re-coloring of the original pixels, where each pixel is assigned the color of its closest cluster center.
