# Neural_Network_Charity_Analysis
## Overview:
The main purpose of this analysis is to use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
## Results:
### _Data Preprocessing_
- `IS_SUCCESSFUL` column is considered as the target for this model, as it contains the data in binary formation for the charity.
- Following columns are considered as the features for the model: `APPLICATION_TYPE`, `AFFILIATION`,  `CLASSIFICATION`,  `USE_CASE`,  `ORGANIZATION`,  `STATUS`, `INCOME_AMT`,  `SPECIAL_CONSIDERATION` and `ASK_AMT`.
- Columns `EIN` an `NAME` are neither targets nor features, and should be removed from the input data.
### _Compiling, Training, and Evaluating the Model_
- For this model two layers were used initially with 80 neurons in first and 50 neurons for the second layer. Further `relu` method is used in the input layers and `sigmoid` activation method in output layer to obtain higher accuracy.
- The model was unable to obtain the accuracy of 75% and the resulted accuracy for the first attempt is 74.14%.
- In attempt to increase the accuracy of the model firstly a `third layer` is added to the model. Further in third attempt additional additional epochs are added but the model still failed to achieve the accuracy of 75%.

## Summary:
- To summarize this deep learning model was unable to achieve accuracy of at least 75% so we can say that this model failed for predictions.
- I recommend trying some supervised machine learning models for this data because the given dataset is a labeled dataset.

