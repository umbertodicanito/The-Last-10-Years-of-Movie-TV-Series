# The Last 10 Years of Movie TV Series
This .pynb concludes the project "The Last 10 Years of Movie & TV Series" that can be found here:

>    Medium Link: www.google.com

The idea behind the project is to analyze the production of entertainment content in the form of Movies and TV Series in the last decade (2012-2021). Following, the main characteristics of the project:

>    Dataset: https://datasets.imdbws.com/ (last update: 31/07/2021)
>    Color Theme: #06f984, #fde802, #ff911a, #fc5d02, #ff00f9
>    Fonts: Bahnschrift SemiBold, Bahnschrift

The goal behind this .pynb work is to clusterize the titles of the top 100 most voted shows in the period 2012-2021, having as attributes the number and the average of the votes, represented by the unique identifier of the titles of the shows (tconst). In order to do this, the K-Means algorithm was chosen.
This algorithm is probably one of the simplest and popular unsupervised machine learning algorithms. Its goal is the same of the problem that is needed to solve here; in fact, citing Wikipedia (https://en.wikipedia.org/wiki/K-means_clustering):

>    "k-means clustering is a method that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster."

Going into details, the pseudocode workflow of the algorithm is the following:

>    1|  Choose k number of clusters
>    2| Select k random points from the data as centroids 
>    3| Assign all the points to the closest cluster centroid 
>    4| Recompute the centroids of newly formed clusters 
>    5| Repeat steps 3 and 4 a number of times arbitrary in order to reach the convergence


From the implementation point of view we chose to use the Scikit Learn (https://scikit-learn.org) one of the best open source libraries for machine learning. Now, let's start with the code.
