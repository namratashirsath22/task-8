📌 Overview

This project demonstrates the complete process of performing K-Means clustering on a dataset, including:

Loading and optionally reducing the dataset to 2D using PCA for visualization.

Using the Elbow Method to find the optimal number of clusters (K).

Visualizing the clusters with color-coded points.

Evaluating clustering quality using the Silhouette Score.

📂 Steps in the Code

Load/Generate Dataset

Generates a synthetic dataset using make_blobs for demonstration.

Can be replaced with your own CSV or real-world dataset.

Optional PCA

Reduces dimensions to 2D for plotting while retaining maximum variance.

Elbow Method

Plots Inertia vs K to help visually choose the optimal number of clusters.

K-Means Clustering

Fits the K-Means model and assigns labels to each data point.

Cluster Visualization

Uses matplotlib to display clusters with unique colors and mark centroids.

Evaluation

Computes the Silhouette Score (ranges from -1 to 1; higher is better).
