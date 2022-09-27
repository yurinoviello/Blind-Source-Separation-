# Blind-Source-Separation-
## Task 

The task consists in decomposing an image obtained as a sum of a two images img1 and img2 into its components.

The network takes in input the sum img1+img2 and returns the predicted components hat_img1 and hat_img2.

No preprocessing is allowed. 

## Data

The source images img1 and img2 come from different datasets: mnist and fashion_mnist, respectively.


## Structure

Write a notebook explaining every step you take and DON'T clear the output of the cells when you submit it.  

You may possibly discuss and provide results for more models, but at most a couple of them should be presented in the notebook.

Make sure to test the model in order to prove robustness and lack of overfitting.

The metric you will need to use to evaluate the results is the mean squared error between predicted and ground truth images.

Evaluate the mse over 20000 samples randomly generated from the two test_sets.

Repeat the computation 10 times and check the standard deviation, that should be very small.

