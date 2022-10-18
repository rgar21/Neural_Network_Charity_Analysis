# Neural_Network_Charity_Analysis

## Overview of Analysis: 
The purpose of this analysis is to create a neural network model for our investment firm. This model will enable the firm to predict the success of future investments using a binary classifier. Using historical data our model will help us determine which investments will be most likely to succeed.

## Results:
  * Data Preprocessing
  
    * The target for our model is the "IS_SUCCESSFUL" column which classifies whether the investment was a success or not.
    * The features for our model are all the columns except for our target which is the "IS_SUCCESSFUL" column.
    * The "EIN" and "NAME" columns are neither targets nor features as they will have no impact on the success of a firm, and thus not impact on our model.
  
  * Compiling, Training, and Evaluating the Model
  
    * I elected to use 3 hidden layers along with 20, 15, and 12 nodes respectively. I believe this will give us a fair chance at creating a balanced and             accurate model.
    * My model was only able to achieve 72.4% accuracy.
    * My first attempt was to remove noisy features, but that did not yield a higher accuracy. My second and third attempts involved increasing the number of         layers, and subsequently the number of nodes per layer.
    
## Summary

In conclusion, our model was only able to reach a 72.4% accuracy rating at a loss of 55.5%. I would not recommend moving forward with this present model as both our accuracy and loss percentages do not meet our sufficient standards. I recommend that we dive deeper into our data looking for more noisy variables and potentially looking into including more data into our sample. After this we can work on including more hidden layers and nodes in order to pursue at least 90% accuracy. 

