# Unsupervised Learning HW

This repository contains a jupyter notebook that reads in data on Crypto Currencies from CryptoCompare. The data is prepped by filtering and removing columns, creating dummy variables for non numeric data values, and standardizing the data. 

From creating dummy variables, the data set went from 4 columns and 532 rows to 98 columns and 532 rows. 

PCA is used to perform dimensionality reduction to specify a specified explained variance. the n_components was adjusted to match the desired explained variance.

t-SNE was then used on the principal components to create a scatter plot to view any distinct clusters of the data. There were no distinct clusters from this data set. 

k-Means was then used to determine the inertia using a for loop. a line plot was created to view a potential elbow plot, however, there was no distinct elbow shape from the plot. 

The outcome of the t-SNE and k-Means methods show that there are no distinct or meaningful clusters that can be made for this dataset. 
