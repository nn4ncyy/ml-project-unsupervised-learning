# machine_learning_project-unsupervised-learning

## Project Goals
The goal of this project is to perform unsupervised learning techniques on a wholesale data dataset in order to discover and unpack patterns in grocery prodict sales. The project involves four main parts: exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and PCA. We will process the data and create visualizations to generate meaningful insights on the data, and effectively use the data to make informed decisions in the future.

### Process
In this project, I applied unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis. Here's the steps I took:

1. Cleaning the data: checking for nulls and imputing missing data.
2. Data Visualization/EDA: Created boxplots and scatterplots to understand the relationships between different variables.
3. Outlier detection: Got rid of any erroneous data points.
4. Correlation Analysis: Determined which variables are highly correlated and which ones are not.
5. Data Transformation: Standardized the variables.
6. Feature Selection: Used principal component analysis to determine the most important features that contribute the most to the overall variance in the dataset.
7. KMeans Clustering: Grouped together similar products based on attributes.
8. Hierarchical Clustering: Identify patterns and group similar data points together using a dendrogram.
9. PCA: Draw conclusions about the underlying structure of wholesale customer data.
   
### Results
Principal Component Analysis (PCA) Reveals Key Variances: The first two principal components explain over 68% of the variance in the dataset, with the first component accounting for 42% and the second for 25.9%. This suggests that these two components capture most of the information in the data, allowing for dimensionality reduction.

Strong Correlations Among Certain Features: The variables "Milk" and "Grocery" have a high positive correlation (0.7), indicating that customers who purchase more milk also tend to purchase more grocery items. Similarly, "Milk" and "Detergents_Paper" are also strongly correlated (0.65), highlighting a potential relationship in purchasing patterns.

Weaker Correlation Between "Region" and Other Variables: "Region" shows very weak correlations with other features, with all correlation values close to zero. This suggests that the region may not significantly impact customer purchasing patterns in terms of the other product categories analyzed.

Outlier Impact on Analysis: During the data preprocessing phase, outliers were identified and removed, and log transformations were applied to reduce the influence of extreme values. The final dataset shows a more consistent distribution of features, helping in both clustering and PCA analysis. These findings help in understanding customer behavior and the relationships between different product categories, which can be used for more targeted marketing or product offerings.

### Challenges
- Deciding when certain outliers were erroneous or not. Some techniques I considered using for removing outliers would've been too harsh and removed too many data points. I had to strike that balance between being accurate but also not overshoot in precision.

### Future Goals
In the future, I would like to create a visualization dashboard to summarize my findings and then use that dashboard to apply the findings to broader business questions. 


