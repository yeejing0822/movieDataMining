The Problem

-The problem faced is the datasets do not implement the supervised learning and unsupervised learning which include classification and clustering. Hence, we are unable to predict the future events from the datasets. Besides, the datasets without supervised learning cannot turn the data into real and actionable insights. Moreover, the datasets without supervised learning could not let people understand the outcomes for the target variable and might cause some unwanted outcomes for the target variable to appear. Furthermore, the datasets without unsupervised learning are unable to perform the complex tasks and cannot help to find patterns of the datasets. In addition,  the following problem is association rule mining  has not been implemented in datasets. This leads to the target behavior being unable to be analyzed and predicted. The machine learning’s program also cannot be built without using associate rules. Moreover, probability of the occurrence of the datasets cannot be identity without using associate rule. 

The classification result and its performance measurement.

Decision Tree:

 ![image](https://github.com/yeejing0822/movieDataMining/assets/86753374/df1c4a35-eab8-420c-9bbc-011c0004a3c1)

  From the Confusion Matrix of decision tree classification , this clearly showed that there are 3923 ratings that are true negative that means predicted value matches with the actual value, and both are negative values. Besides, 1078 ratings are false negative (type 2 error )that means the predicted values were falsely predicted, the actual value of rating was positive but the model had predicted the negative value of ratings. Moreover, 165 ratings are false positive (type 1 error ) that means the predicted ratings value is falsely predicted. The actual rating value is negative but the model predicted the positive rating value. Furthermore, there are 183 ratings value is true positive that define as predicted ratings value matches with the actual ratings value, and both are positive rating values.

 Precision is defined as how many of the correctly predicted events actually turned out to be positive. It is using the true positive value that divides the sum of true positive value and false positive value. Besides, the recall is defined as how many of the actual positive events are able to predict correctly in our model. It is using true positive value to divide the sum of true positive value and false negative value.When we view the classification report, depending on the weighted average of the ratings , the precision is 0.72 means that 72% percent of the correctly predicted events had changed to be positive events. Moreover, when we view the recall value of the weighted average of the ratings, it is 0.77 means that 77% of the positives were predicted successfully by the model. In this case, precision is more important than recall since wrong results will confuse people when choosing movies to watch depending on ratings. 

  F1-score is the harmonic mean for precision and recall which combined these 2 metrics. The maximum value is 1 when precision equal to recall and it’s minimum is 0. Based on the F1-score of weighted average, it is 0.71 that is closer to 1 which can be said that precision and recall are almost equal.

Logistic Regression:

![image](https://github.com/yeejing0822/movieDataMining/assets/86753374/c7a8fdee-9101-46f2-b95c-fffc1ded3a2e)

  
 From the Confusion Matrix of logistic regression classification , this clearly showed that there are 3950 ratings that are true negative that means predicted value matches with the actual value, and both are negative values. Besides, 1090 ratings are false negative (type 2 error )that means the predicted values were falsely predicted, the actual value of rating was positive but the model had predicted the negative value of ratings. Moreover, 138 ratings are false positive (type 1 error ) that means the predicted ratings value is falsely predicted. The actual rating value is negative but the model predicted the positive rating value. Furthermore, there are 171 ratings value is true positive that define as predicted ratings value matches with the actual ratings value, and both are positive rating values.

 Precision is defined as how many of the correctly predicted events actually turned out to be positive. It is using the true positive value that divides the sum of true positive value and false positive value. Besides, the recall is defined as how many of the actual positive events are able to predict correctly in our model. It is using true positive value to divide the sum of true positive value and false negative value.When we view the classification report, depending on the weighted average of the ratings , the precision is 0.73 means that 73% percent of the correctly predicted events had changed to be positive events. Moreover, when we view the recall value of the weighted average of the ratings, it is 0.77 means that 77% of the positives were predicted successfully by the model. In this case, precision is more important than recall since wrong results will confuse people when choosing movies to watch depending on ratings. 

  F1-score is the harmonic mean for precision and recall which combined these 2 metrics. The maximum value is 1 when precision equal to recall and it’s minimum is 0. Based on the F1-score of weighted average, it is 0.71 that is closer to 1 which can be said that precision and recall are almost equal.

Support Vector Machine:

![image](https://github.com/yeejing0822/movieDataMining/assets/86753374/c32e4606-b333-4d0e-801b-aabd44667635)

 
 From the Confusion Matrix of support vector classification , this clearly showed that there are 0 ratings that are true negative that means predicted value matches with the actual value, and both are negative values. Besides, 0 ratings are false negative (type 2 error )that means the predicted values were falsely predicted, the actual value of rating was positive but the model had predicted the negative value of ratings. Moreover, 1275 ratings are false positive (type 1 error ) that means the predicted ratings value is falsely predicted. The actual rating value is negative but the model predicted the positive rating value. Furthermore, there are 4074 ratings value is true positive that define as predicted ratings value matches with the actual ratings value, and both are positive rating values.

 Precision is defined as how many of the correctly predicted events actually turned out to be positive. It is using the true positive value that divides the sum of true positive value and false positive value. Besides, the recall is defined as how many of the actual positive events are able to predict correctly in our model. It is using true positive value to divide the sum of true positive value and false negative value.When we view the classification report, depending on the weighted average of the ratings , the precision is 0.58 means that 58% percent of the correctly predicted events had changed to be positive events. Moreover, when we view the recall value of the weighted average of the ratings, it is 0.76 means that 76% of the positives were predicted successfully by the model. In this case, precision is more important than recall since wrong results will confuse people when choosing movies to watch depending on ratings. 

  F1-score is the harmonic mean for precision and recall which combined these 2 metrics. The maximum value is 1 when precision equal to recall and it’s minimum is 0. Based on the F1-score of weighted average, it is 0.66 that is closer to 1 (due to over 0.5) which can be said that precision and recall are almost equal.


Naive Bayesian:

 ![image](https://github.com/yeejing0822/movieDataMining/assets/86753374/7bda1556-ed53-4cdc-9316-f60b60de4f50)

  From the Confusion Matrix of naive bayesian classification , this clearly showed that there are 4074 ratings that are true negative that means predicted value matches with the actual value, and both are negative values. Besides, 1275 ratings are false negative (type 2 error )that means the predicted values were falsely predicted, the actual value of rating was positive but the model had predicted the negative value of ratings. Moreover, 0 ratings are false positive (type 1 error ) that means the predicted ratings value is falsely predicted. The actual rating value is negative but the model predicted the positive rating value. Furthermore, there are 0 ratings values that are true positive that define as predicted ratings value matches with the actual ratings value, and both are positive rating values.

   Precision is defined as how many of the correctly predicted events actually turned out to be positive. It is using the true positive value that divides the sum of true positive value and false positive value. Besides, the recall is defined as how many of the actual positive events are able to predict correctly in our model. It is using true positive value to divide the sum of true positive value and false negative value.When we view the classification report, depending on the weighted average of the ratings , the precision is 0.58 means that 58% percent of the correctly predicted events had changed to be positive events. Moreover, when we view the recall value of the weighted average of the ratings, it is 0.76 means that 76% of the positives were predicted successfully by the model. In this case, precision is more important than recall since wrong results will confuse people when choosing movies to watch depending on ratings. 

  F1-score is the harmonic mean for precision and recall which combined these 2 metrics. The maximum value is 1 when precision equal to recall and it’s minimum is 0. Based on the F1-score of weighted average, it is 0.66 that is closer to 1 (due to over 0.5) which can be said that precision and recall are almost equal.

  KNN:
  
 ![image](https://github.com/yeejing0822/movieDataMining/assets/86753374/d61312c1-53d4-498e-a186-6ea5bc589313)

  From the Confusion Matrix of KNN classification , there are 5*5 array that defined the first line of array as strongly negative to the last line of array as strongly positive for the five elements in rows and columns. For example, there is 1 value on the first column which means it is strongly negative for the predicted result and it is positioned at the second row of the array which means it is negative for the actual result.

   Precision is defined as how many of the correctly predicted events actually turned out to be positive. It is using the true positive value that divides the sum of true positive value and false positive value. Besides, the recall is defined as how many of the actual positive events are able to predict correctly in our model. It is using true positive value to divide the sum of true positive value and false negative value.When we view the classification report, depending on the weighted average of the ratings , the precision is 0.20 means that 20% percent of the correctly predicted events had changed to be positive events. Moreover, when we view the recall value of the weighted average of the ratings, it is 0.20 means that 20% of the positives were predicted successfully by the model. In this case, precision is more important than recall since wrong results will confuse people when choosing movies to watch depending on ratings. 

  F1-score is the harmonic mean for precision and recall which combined these 2 metrics. The maximum value is 1 when precision equal to recall and it’s minimum is 0. Based on the F1-score of weighted average, it is 0.20 that is closer to 0 (due to no over 0.5) which can be said that precision and recall are not equal.

Conclusion:

In conclusion, when comparing these classification models’ precision depend on weighted average, the best model is logistic regression which has the highest precision among the classification models which is 0.73 means 73% percent of the correctly predicted events had changed to be positive events. Besides, when comparing these classification models’ recall depend on weighted average, the best model is decision tree and logistic regression which have the highest recall among the classification models which is 0.77 means 77% of the positives were predicted successfully by the model.


