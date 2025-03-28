Spotify Audio Features Clustering Analysis
This project explores and clusters Spotify audio features using unsupervised learning techniques. It provides insights into the grouping of tracks based on their inherent audio properties.

Overview
Dataset: A collection of Spotify tracks with key audio features such as danceability, energy, loudness, speechiness, acousticness, instrumentalness, liveness, valence, tempo, and duration.

Objective: To cluster tracks into groups using DBSCAN and evaluate the clustering performance using a silhouette score (achieved above 90%).

Visualizations: Data distributions, correlation heatmaps, PCA plots, pairplots, and scatter plots to illustrate the cluster characteristics.

Key Steps
Data Exploration & Visualization

Displayed dataset information and the first few rows.

Visualized feature distributions with histograms and KDE plots.

Generated a correlation heatmap to examine relationships among audio features.

Data Preprocessing

Selected relevant audio features.

Standardized the features using StandardScaler.

Clustering with DBSCAN

Used a k-distance plot for optimal epsilon parameter estimation.

Applied DBSCAN clustering with tuned parameters (eps = 0.4, min_samples = 2).

Cluster Evaluation & Visualization

Reduced data dimensions using PCA for visual cluster separation.

Calculated a silhouette score (above 90%) to validate the quality of the clusters.

Provided additional pairplots and scatter plots to further interpret the clustering results.

Technologies Used
Python

Pandas & NumPy

Seaborn & Matplotlib

Scikit-learn (StandardScaler, NearestNeighbors, DBSCAN, PCA, TSNE, silhouette_score)

Jupyter Notebook

Results & Insights

Effective Clustering:
By leveraging DBSCAN, the project successfully clustered tracks based on their audio features with a silhouette score above 90%, indicating high cohesion within clusters.

Visual Interpretations:
PCA visualizations and pairplots provided clear insights into the distribution and separation of clusters.

Future Enhancements:
Consider experimenting with other clustering methods or incorporating additional features to further refine the clusters.

License
This project is licensed under the MIT License.

Connect
For more details and to explore the full code, check out the repository on GitHub: https://github.com/yourusername/spotify-clustering

Let's keep the rhythm of data exploration and clustering alive! 🎵🚀
