# K-Means Clustering with MNIST Dataset

This script performs K-Means clustering on the MNIST dataset using scikit-learn. It preprocesses the data, calculates cluster accuracy, and visualizes the clusters.

## Preprocessing Data

The `preprocess_data` function reshapes and scales the input data to prepare it for clustering. It flattens the images and normalizes pixel values to the range [0, 1].

## Cluster Accuracy Calculation

The `calculate_cluster_accuracy` function computes the accuracy of each cluster by finding the most common label within the cluster and comparing it with the true labels. The overall accuracy is then calculated based on correct predictions.

## Visualizing Clusters

The `visualize_clusters` function displays a sample of images from each cluster for visual inspection.

## Main Function

The `main` function loads the MNIST dataset, preprocesses the data, and performs K-Means clustering for different values of `k`. It then visualizes the clusters and computes the accuracy for each value of `k`.

## Dependencies

- matplotlib
- numpy
- scikit-learn
- keras (for loading the MNIST dataset)
