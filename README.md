# customer-segamentation-banking
This is a banking customer segmentation capstone project for Crystal System. 

# Customer Segmentation Using Clustering Algorithms

This project aims to identify distinct customer segments based on their purchasing behavior using clustering algorithms. The analysis is performed on a dataset containing customer transaction data, and the results provide insights into the characteristics of different customer groups, enabling data-driven decision-making for targeted marketing strategies and improved customer satisfaction.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Requirements](#requirements)
3. [Dataset](#dataset)
4. [Clustering Algorithms](#clustering-algorithms)
5. [Evaluation Metrics](#evaluation-metrics)
6. [Usage](#usage)
7. [Results](#results)
8. [Conclusion](#conclusion)

## Project Overview

The main objective of this project is to segment customers based on their purchasing behavior using various clustering algorithms, such as K-means, Hierarchical Clustering (Agglomerative Clustering), and DBSCAN. The results of the clustering algorithms are evaluated using metrics like Silhouette Coefficient and Calinski-Harabasz Index to compare their performance and choose the most appropriate method for the dataset.

## Requirements

- Python 3.6 or later
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## Dataset

The dataset used in this project contains customer transaction data, including variables such as the number of purchases, total transaction value, and recency of purchases. The dataset should be cleaned and preprocessed before applying clustering algorithms.

## Clustering Algorithms

1. **K-means Clustering**: This algorithm partitions the data into K distinct clusters based on their distance to the cluster centroids. The number of clusters, K, must be specified beforehand.

2. **Hierarchical Clustering (Agglomerative Clustering)**: This method builds a hierarchy of clusters by iteratively merging pairs of clusters that are closest to each other. The optimal number of clusters can be determined using a dendrogram.

3. **DBSCAN Clustering**: This density-based clustering algorithm identifies clusters of varying densities and shapes, as well as noise points. It requires specifying the maximum distance between points in the same cluster (eps) and the minimum number of points required to form a dense region (min_samples).

## Evaluation Metrics

1. **Silhouette Coefficient**: This metric measures the similarity of an observation to its own cluster compared to other clusters. Values range from -1 to 1, with higher values indicating better clustering performance.

2. **Calinski-Harabasz Index**: A higher value of this index indicates that the clusters are well separated and compact, suggesting that the clustering model is appropriate for the data.

## Usage

1. Load the dataset into a pandas DataFrame.
2. Clean and preprocess the data, including scaling the features.
3. Apply the clustering algorithms to the preprocessed data.
4. Evaluate the performance of the clustering algorithms using the Silhouette Coefficient and Calinski-Harabasz Index.
5. Visualize the results using appropriate plots (e.g., scatter plots, bar charts, etc.).
6. Analyze the findings and compare the results of the different clustering algorithms.

## Results

The results of the clustering algorithms provide insights into the characteristics of different customer segments. Please refer to the [Findings](#findings) section of the project report for a detailed discussion of the key observations.

## Conclusion

This project demonstrates the utility of clustering algorithms in identifying distinct customer segments based on their purchasing behavior. By evaluating the performance of K-means, Hierarchical Clustering, and DBSCAN algorithms, we gained valuable insights into the characteristics of different customer groups, which can inform data-driven decision-making for targeted marketing strategies and improved customer satisfaction. Future research could explore additional clustering algorithms, incorporate other customer attributes, or implement predictiveanalytics to further enhance the understanding of customer behavior and preferences.

## Acknowledgements

We would like to express our gratitude to everyone who contributed to the success of this project. This includes the project team, instructors, and colleagues who provided valuable feedback and guidance throughout the project. We also appreciate the creators and maintainers of the Python libraries used in this project for their efforts in making these tools accessible and easy to use.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). The dataset used in this project belongs to its respective owner(s) and is used for educational purposes only.

## Contact

If you have any questions, comments, or suggestions, please feel free to contact the project team via email or social media.

**Happy clustering!**
