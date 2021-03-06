# Neural_Network_Charity_Analysis
## Overview of the Analysis
For this challenge we were tasked dto help Beck's learn about neural networks and how to design and train these models using TensorFlow library. We had to create a deep learning neural network capable of interpreting large complex datasets. In order, for to decided which organizations should recieve donations from The Alphabet Soup Foundation.

## Results
### Data Preprocessing 
1. What variable(s) are considered the target(s) for your model?
The variable that is considered the target for my model is the IS_SUCCESSFUL column.

2. What variable(s) are considered to be the features for your model?
The variables that are considered to be the featured for my model are APPLICATION_TYPE, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, and INCOME_AMT. 

3. What variable(s) are neither targets nor features, and should be removed from the input data?
The variables that were neither a target or feature was EIN and NAME and was removed from the input data.

### Compiling, Training, and Evaluating the Model
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
In layer 1, we started with 80 neurons with activation sigmoid. For layer 2, we did 20 neurons and changed to activation relu. For layer 3, we chose 40 neurons and actiavtion sigmoid. Lastly layer 4 had 20 neurons and was a sigmoid activation once again. 

2. Were you able to achieve the target model performance?
No, I was not able to to achieve the target model performance.
![Screen Shot 2022-07-17 at 4 15 16 PM](https://user-images.githubusercontent.com/98666231/179428751-006a5172-0f52-45e8-ae6a-d8e487c4addf.png)
![Screen Shot 2022-07-17 at 4 12 12 PM](https://user-images.githubusercontent.com/98666231/179428755-0d3f9e21-bef6-41e3-a0a0-6cdbab7643d4.png)
![Screen Shot 2022-07-17 at 4 09 49 PM](https://user-images.githubusercontent.com/98666231/179428757-18525cec-69f9-44bd-a44d-532e52243b8f.png)


3. What steps did you take to try and increase model performance?
If we increase the neurons on one of the hidden layers. We can improve the model performance and I changed my epochs to 100.

## Summary
The model gave a 72% accuracy, which did not reach the target model. I would recommend using the random forest classifer because it will randomly sample the preprocessed data and buliding several smaller and simpler decision trees. Random forest classifer is also robust to outliers and nonlinear data and it runs well on large datasets.
