# Credit Card Clustering (PCA + Kmeans)

Code Written in Python using Jupyter Notebook. Open the notebook [here](https://github.com/sshreyas999/Credit-Card-Clustering-PCA-Kmeans/blob/main/Credit%20Card%20Clustering%20(PCA%20%2B%20Kmeans).ipynb) for code and thorough analysis.


## Objective  
Our main task is to cluster credit card users into different groups and see if we can find any meaningful patterns. We will use Principal Component Analysis **(PCA)** to reduce the dimension of the feature space and then use the **K-means** algorithm to find clusters.

## Dataset
The dataset contains 8950 observations and 18 attributes for each observation. Dataset is included in the repository.

## Outline  
The following procedures are carried out in the notebook:
### Preprocessing the Dataset  
Determine what attributes are useful for the task at hand. Handle missing values, standardize, and normalize the data.
### PCA
Use PCA to reduce the dimensionality of our data. Select an appropriate number of components and analyze total variance explained. Interpret to make sense of the principal components. 
### Kmeans Clustering
Cluster using the Kmeans algorithm and find the optimum numebr of clusters. Use **within cluster sum-of-squares** to arrive at the result. 
### Interpretation & Conclusion 
Visualize the clustered data, draw a decision boundary and try to interpret the clusters in context to the problem at hand. 

## Conclusion
We chose 2 principal components in order to visualize results. In this scenario, segregating into 3 clusters was appropriate.  
