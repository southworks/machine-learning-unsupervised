# Overview
In this spike we worked on Clustering using K-Means. The notebook and dataset files are in Clustering_Spike directory.
We chose clustering because is one of the most common applications of unsupervised learning used to identify clusters of data objects in a dataset. There are many different types of clustering methods, but k-means is one of the oldest and most documented solution.

## K-Means
This method, randomly selects `k` centroids, where k is equal to the number of clusters. Then, start the iterative process where K-Means assigns each data point to its nearest centroid and computes the mean of all the points for each cluster and sets the new centroid.


# Folder Map
 - `Clustering_Spike/`
   - `clustering_spike.ipynb`: Notebook with the scripts to load any of the three different datasets and run the K-Means algorithm over one of them.
   - `generated_dataset/`: Directory which contains the files corresponding to the synthetic dataset downloaded from [here](http://cs.joensuu.fi/sipu/datasets/). We converted the .txt file to a .csv.

# How to Run

1. Activate ml-workshop conda environment.
2. Open Clustering_Spike/clustering_spike.ipynb notebook.
3. Run the cells of the chosen dataset.
   - To run the auto-generated dataset, run the following cells: [1,5,6,7,8,9,10,11,12,13,14,15,16,17]
   - To run the TCGA dataset, run the following cells (if the dataset is already downloaded you can skip the 2nd cell) : [1,2,3,6,7,8,9,10,11,12,13,14,15,16,17]