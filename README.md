# Black-Friday-Sale

Problem : 
Estimate the purchase amount.

Dataset Description :
Dataset contains around 550000 rows of data. Dataset had the description of the customers and the things they bought.

Model Description:
I have used the sci-kit learn package implementation of Random Forest Regressor to estimate the purchase amount. I also used sci-kit learn package's Standard Scaler for feature scaling. 

Journey :
I started with simple linear regression to see what features were important. Product_ID turned out to be the most important feature. Then I tried a decision tree regressor which didn't perform very well(r2_score of mere 0.2), which guided me in the direction of ensemble methods, in this case Random Forest worked the best.
