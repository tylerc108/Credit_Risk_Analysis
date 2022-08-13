# Credit_Risk_Analysis

## Overview

For this analysis, we analyzed the risk for a credit lender called LendingClub, a peer-to-peer lending services company, to help them predict which loans would most likely turn out to be good loans and which would most likely turn out to be bad. We received a large data set containg information on loans that the company had previously given out and used this to create our model. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.


Output for Naive Random Oversampling:

<img width="737" alt="Screen Shot 2022-08-13 at 12 32 58 PM" src="https://user-images.githubusercontent.com/103055666/184502816-ea9af515-f85f-4e2d-be10-1e71a06736b5.png">

* The accuracy score was around .65, meaning approximately 65 predictions out of 100 were correct. 
* The precision was calculated to be .99, which is very high and means that 99% of predicted true outcomes were in fact true. 
* The sensitivity/recall was calculated .59, meaning 59% of high-risk loans were detected. Because this model has high precision, the trade-off is that it has relatively low sensitivity.

Output for SMOTE:

<img width="721" alt="Screen Shot 2022-08-13 at 12 33 19 PM" src="https://user-images.githubusercontent.com/103055666/184502834-45c8c422-db6b-42c6-b817-e8882d659f39.png">

* The accuracy score was around .66, meaning approximately 66 predictions out of 100 were correct. 
* The precision was calculated to be .99, which is very high and means that 99% of predicted true outcomes were in fact true. 
* The sensitivity/recall was calculated .69, meaning 69% of high-risk loans were detected. 

Output for Undersampling:

<img width="734" alt="Screen Shot 2022-08-13 at 12 33 43 PM" src="https://user-images.githubusercontent.com/103055666/184502853-d69517c0-0457-4a43-839e-535cb8d56834.png">


* The accuracy score was around .54, meaning approximately 54 predictions out of 100 were correct. 
* The precision was calculated to be .99, which is very high and means that 99% of predicted true outcomes were in fact true. 
* The sensitivity/recall was calculated .40, meaning 40% of high-risk loans were detected. 

Output for Combination Sampling:

<img width="713" alt="Screen Shot 2022-08-13 at 12 42 50 PM" src="https://user-images.githubusercontent.com/103055666/184503167-5e079e97-8f3b-4519-bd89-5927df6921c9.png">


* The accuracy score was around .64, meaning approximately 64 predictions out of 100 were correct. 
* The precision was calculated to be .99, which is very high and means that 99% of predicted true outcomes were in fact true. 
* The sensitivity/recall was calculated .58, meaning 58% of high-risk loans were detected. 

Output for Balanced Random Forest Classifier:

<img width="733" alt="Screen Shot 2022-08-13 at 12 37 54 PM" src="https://user-images.githubusercontent.com/103055666/184502997-a0a16e33-dede-4901-893a-0dc39661805b.png">

* The accuracy score was around .79, meaning approximately 79 predictions out of 100 were correct. 
* The precision was calculated to be .99, which is very high and means that 99% of predicted true outcomes were in fact true. 
* The sensitivity/recall was calculated .87, meaning 87% of high-risk loans were detected. 

Output for Easy Ensemble

<img width="729" alt="Screen Shot 2022-08-13 at 12 38 09 PM" src="https://user-images.githubusercontent.com/103055666/184503005-4051e3ba-98f9-4a2e-b127-6ada6ecfd8ad.png">

* The accuracy score was around .93, meaning approximately 93 predictions out of 100 were correct. 
* The precision was calculated to be .99, which is very high and means that 99% of predicted true outcomes were in fact true. 
* The sensitivity/recall was calculated .94, meaning 94% of high-risk loans were detected.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

* We would certainly recommend using the Easy Ensemble model out of the six that we created. This model is much better than the others in both accuracy and sensitivity and equal to the others in precision, so there are truly no downsides to choosing this model out of the six. 

