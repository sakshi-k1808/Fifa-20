# FIFA 20 Player Analysis and Clustering

This repository contains a Jupyter notebook (`Fifa20.ipynb`) that performs an in-depth analysis and clustering of FIFA 20 player data. The project aims to identify distinct player types and segments through statistical and visual methods.

## Project Description

The `Fifa20.ipynb` notebook processes a dataset of FIFA 20 players to uncover underlying patterns and group similar players together. It leverages various data science techniques, including data loading, preprocessing, dimensionality reduction (PCA), and unsupervised machine learning (KMeans clustering).

## Data Source

The analysis relies on player data from FIFA 20, which is expected to be available in a CSV file named `players_20.csv`.

## Key Libraries and Technologies

The following Python libraries are utilized in this project:
* `pandas` for data manipulation and analysis
* `numpy` for numerical operations
* `seaborn` for statistical data visualization
* `matplotlib.pyplot` for creating static, interactive, and animated visualizations
* `warnings` to filter warnings during execution

## Methodology and Analysis

The notebook employs the following key methodologies:
* **Data Loading**: Reads player data from `players_20.csv` into a pandas DataFrame.
* **Clustering**: Implements KMeans clustering with `k=3` to group players into distinct categories.
* **Dimensionality Reduction**: Utilizes Principal Component Analysis (PCA) to reduce the dimensionality of the data, enabling easier visualization and interpretation of clusters.
* **Cluster Evaluation**: The effectiveness of the clustering is evaluated using a silhouette score, which achieved a strong result of 0.58.

## Results and Conclusion

The clustering analysis, particularly with KMeans (k=3), is found to be statistically and visually sound. The resulting clusters are distinct, compact, and meaningfully separated in the PCA space. This demonstrates production-quality clustering suitable for exploratory analysis or downstream applications such as identifying customer segments, player types, or other subgroups.
