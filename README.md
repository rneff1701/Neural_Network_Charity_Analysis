# Neural_Network_Charity_Analysis

##Overview
Utilize machine learning to analyze the success of charity donations.

##Results
Data Preprocessing
- What variable(s) are considered the target(s) for your model?  The IS_SUCCESSFUL column contains data on whether the charity donation was successful.
- What variable(s) are considered to be the features for your model?  The columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
- What variable(s) are neither targets nor features, and should be removed from the input data?  EIN and NAME were removed.

Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why? Two hidden layers and 80 and 30 neurons.  The activation function ReLU was used for the hidden layers. 
- Were you able to achieve the target model performance?  No, the model accuracy was under 75%.
- What steps did you take to try and increase model performance?  Bucketing was applied to ASK_AMT, a model with three hidden layers was used, and then the TANH activation function was used.

##Summary
After trying additional changes the model was not able to reach 75% accuracy.
