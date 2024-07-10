# CryptoClustering
# Project Overview

This project focuses on clustering cryptocurrencies based on the price change percentages over various periods of time using K-Means clustering. This analysis aimed to identify patterns and group cryptocurrencies. This project also uses PCA (Principal Component Analysis) to facilitate more efficient clustering.

## Dataset

Dataset used is a CSV file named 'crypto_market_data.csv' and is located in the 'Resources' directory.

# Prerequisites
Ensure you have the following libraries installed:
- Pandas
- Hvplot
- Scikit-learn
- Warnings

# Conclusion

Using PCA for dimensionality reduction resulted in tighter clusters, this indicates that fewer features can effectively represent the data for clustering purposes. This approach simplifies the model without losing significant information.
