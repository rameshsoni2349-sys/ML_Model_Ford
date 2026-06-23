# ML_Model_Ford
Ford car model (price prediction) though linear Regression 

Note important poin example :

1.  Histogram ek graph hai jo dikhata hai ki data kis range me kitni baar aata hai.

-> "Histplot is used to visualize the distribution of a numerical feature. It helps identify the most common value ranges, skewness, spread, and outliers in the data.
  In the price column, it shows how car prices are distributed across different ranges."

2. Bar Plot tab use karte hain jab hume categories ko compare karna ho.
-> Bar plot is used to compare values across different categories. It helps visualize differences between groups and is commonly used to show averages, counts, or other aggregated statistics for categorical variables. For example, a bar plot of year vs price shows the average car price for each year.

3. Boxplot is used to understand the distribution of a numerical variable and detect outliers. It shows the median, spread of data (IQR), and unusual values. When comparing groups, such as tax vs price, it helps compare price distributions across different tax categories

4. from sklearn.model_selection import train_test_split X_train, X_test , y_train, y_test = train_test_split(one_hot_encode, y, test_size=0.20, random_state=42)

  When do we use train_test_split()?
  
  Machine Learning model train karne se pehle dataset ko do parts me divide karne ke liye use karte hain:
  
  Training Data (80%) → Model ko sikhane ke liye.
  Testing Data (20%) → Model ki performance check karne ke liye.
  Example
  
  Agar 1000 rows hain:
  
  Training Data = 800 rows
  Testing Data  = 200 rows
  Model 800 rows se learn karega.
  200 unseen rows par test hoga.
  Parameters
  
