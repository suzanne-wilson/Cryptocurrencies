# Cryptocurrencies - Module 18 Challenge

The goals for this challenge are:

- Prepare the data for dimensions reduction with PCA and clustering using K-means.
- Reduce data dimensions using PCA algorithms from sklearn.
- Predict clusters using cryptocurrencies data using the K-means algorithm form sklearn.
- Create some plots and data tables to present your results.

### Prepare the data for dimensions reduction with PCA and clustering using K-means.
The data on cryptocurrencies was imported and cleaned according to instructions.  There were 1,252 rows on import.  After all preprocessing, 532 rows remained.  Dummy variables were created for non-numeric columns, and numeric columns were scaled using StandardScaler.

### Reduce data dimensions using PCA algorithms from sklearn.
Dimensions of the data were reduced from 98 to 3 using PCA.  

### Predict clusters using cryptocurrencies data using the K-means algorithm form sklearn.
An elbow plot was created, and the elbow appeared to be at n=4 clusters.

### Create some plots and data tables to present your results.
A 3d plot, where each axis represented a principal component, was created using plotly.  In addition, a new dataframe which included the original key variables and the predicted cluster for that row was created using hvplot.table.  Finally, a 2D scatter plot comparing Total Coins Mined and Total Coin Supply was plotted.
