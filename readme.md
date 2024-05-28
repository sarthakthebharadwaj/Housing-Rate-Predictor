This was my spring 24 project for 445 , where we used two well known datasets Boston housing and miami housing datasets. 
We cleaned the dataset and preprossed by dropping the na values, and the emplty rows / columns.

We used 6 algorithms and made a graph showig how accurate each algorithm was in predicting the output. 
The 6 algorithms were linear regression , KNN ,Decision tree regressor, Random forest regressor, SVR and Neural Network where in both casses SVR gave -ve result predictiosn.

In future we can add other algorithms to see how well they behave.

As a measure of good fit used the R2 score here , IN SVR probably the summation of (y-y^) raised to the power 2 was more than summation of (y-ybar) raised to the power 2 , which is why we had negetive r2 in both the datasets.
