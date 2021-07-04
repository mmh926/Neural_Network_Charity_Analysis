

# Neural Network Charity Analysis READMe

## PURPOSE:
The purpose of this analysis is to report on the performance of the deep learning model you created for AlphabetSoup.

In this analysis I used Machine Learning, Pandas and the Scikit-Learn’s StandardScaler() to preprocess the dataset in order to compile, train, and evaluate the neural network mode.

I used machine learning and neural networks features in the provided dataset to help Beks, a Data Scientist and Programmer, to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup, a philanthropic foundation dedicated to helping organizations that protect the environment, improve people’s well-being, and unify the world.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are several columns that capture metadata about each organization, such as the following:

•	EIN and NAME—Identification columns
•	APPLICATION_TYPE—Alphabet Soup application type
•	AFFILIATION—Affiliated sector of industry
•	CLASSIFICATION—Government organization classification
•	USE_CASE—Use case for funding
•	ORGANIZATION—Organization type
•	STATUS—Active status
•	INCOME_AMT—Income classification
•	SPECIAL_CONSIDERATIONS—Special consideration for application
•	ASK_AMT—Funding amount requested
•	IS_SUCCESSFUL—Was the money used effectively

## RESULTS:
### Data Processing
•	What variable(s) are considered the target(s) for your model? In this model, the target(s), or input values commonly referred to as independent variables or “X” in TensorFlow documentation are: 
IS_SUCCESSFUL
 ![image](https://user-images.githubusercontent.com/78371845/124371835-b4e16a00-dc53-11eb-90d0-cf0bc6df0bb0.png)


•	What variable(s) are considered to be the features for your model? In this model, the features, of target output values commonly referred to as dependent variables or “y” in TensorFlow documentation are:
•	APPLICATION_TYPE
•	AFFILIATION
•	CLASSIFICATION
•	USE_CASE
•	ORGANIZATION
•	STATUS
•	INCOME_AMT
•	SPECIAL_CONSIDERATIONS
•	ASK_AMT

•	What variable(s) are neither targets nor features, and should be removed from the input data? The variables that are neither targets nor features, and should be removed from the input data are:
•	EIN
•	NAME

### Compiling, Training, and Evaluating the Model
•	How many neurons, layers, and activation functions did you select for your neural network model, and why?
•	number_input_features = 43
•	hidden_nodes_layer1 = 80
•	hidden_nodes_layer2 = 30
•	
 ![image](https://user-images.githubusercontent.com/78371845/124371842-c0cd2c00-dc53-11eb-935c-e00b6e952e95.png)


•	Were you able to achieve the target model performance? I was not able to achieve target model performance. I achieved 72% accuracy. 
 ![image](https://user-images.githubusercontent.com/78371845/124371847-ca569400-dc53-11eb-9799-d61376b9e247.png)


•	What steps did you take to try and increase model performance?
Several attempts to increase the accuracy of the model were taken.


## SUMMARY:
In summary, the overall results of the deep learning module were very close but not successful, accuracy wise. Also a different model may be able to solve the classification problem. 
