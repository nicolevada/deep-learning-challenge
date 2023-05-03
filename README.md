# deep-learning-challenge
**Data Preprocessing**
* The target variable for the model is 'IS_SUCCESSFUL', which indicates whether or not a donation was used effectively.
* The features for the model include all columns except for 'EIN' and 'NAME', which are non-beneficial identification columns.
* The non-categorical columns 'STATUS', 'SPECIAL_CONSIDERATIONS', and 'ASK_AMT' are also removed from the input data because they are neither targets nor features.
Compiling, Training, and Evaluating the Model
* For the neural network model, two hidden layers with 80 and 30 neurons, respectively, were selected, along with a ReLU activation function for each hidden layer and a sigmoid activation function for the output layer.
* The model was compiled with binary crossentropy as the loss function, Adam as the optimizer, and accuracy as the evaluation metric.
* The target model performance was not achieved, as the final accuracy score was only around 72%.
* Several attempts were made to increase model performance, including using a larger neural network with more layers and neurons, adjusting the learning rate of the optimizer, and increasing the number of epochs. However, none of these attempts resulted in a significant increase in model performance.

**Summary**
* Overall, the deep learning model achieved a moderate level of accuracy for predicting whether or not a donation was used effectively.


* A different model that could potentially solve this classification problem is a Random Forest classifier. This model could use a decision tree-based approach to determine the most important features for predicting whether or not a donation is used effectively, and could potentially achieve higher accuracy than the neural network model.
