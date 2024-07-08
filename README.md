# Crypto Clustering

From Module 19: Unsupervised Learning from the Data Analytics Boot Camp by Monash University and EdX.

By implementing skills learnt throughout the module, an attempt at the challenge has been submitted here.

## Contents

- `Resources` folder
  - `crypto_market_data.csv` file
- `Crypto_Clustering.ipynb` file with main code

## Explanation

The data was first normalised by using `StandardScaler()`. Then the best value for  (k = 4) was found using the scaled data and used to create a scatter plot with 4 clusters. The data was then optimised with Principal Component Analysis (PCA) and the best value for k remained unchanged. Another scatter plot was created with 4 clusters and the resulting graphs were compared (scaled data against PCA data). A composite plot was used to make it visually easier to compare.

## Credits

- All data and starter codes were given.
- Code used were taken from class activities and modified where necessary.