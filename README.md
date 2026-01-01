# WIDS-25-Week-2
Here is the submission for Study of Models WIDS 25 submission for week 2
I used housing dataset from external source rather than sklearn library because it was not displaying categorical attributes
All tasks are coded in an order as specified in assignemnt 2 quesiton:
Load the California Housing dataset from sklearn.datasets.Use pandas library.Deliverables:
     Shape of dataset
     Column names
     First 10 rows

Use .describe() , .info() for understanding data.Which feature has largest variance?
Univariate Analysis (Histograms)
Plot histograms for all numeric columns with proper labelling of axis.
Try:
different bins
Explain most widely used methods to eliminate skewness of column features in comments.
Use Box plot for each feature to detect outliers in MedInc
AveRooms,Population
Correlation Heatmap:Compute correlation matrix
,Plot a heatmap
 Latitude/Longitude Visualization
Scatter plot:
Longitude vs Latitude
Color (cmap) by MedHouseVal
Point size based on Population
Explain why scaling is required before PCA.
Apply PCA on features
Plot explained variance ratio
Choose top 2 principal components
Scatter plot:PC1 vs PC2
Color points by MedHouseVal
Create a scikit-learn Pipeline for multiple linear regression and print coefficients- intercept matrix (exclude latitude and longitude in this final model becoz that is not relevant data : use correlation matrix to prove this point also)
Evaluate model on metrics of MSE loss, MAE loss, R2 score , adjusted R2 score. 
Is high R2 score always good? Is low training loss always preferred?
Plot:Predicted vs Actual
Residuals vs Predicted values
