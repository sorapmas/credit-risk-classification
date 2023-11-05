# Credit Risk Classification Challenge

## Background:
The purpose of this respistory is to use various techniques to train and evaluate a model based on loan risk. The dataset under the resources folder is a historical lending activity from a peer-to-peer lending services company which will be used to build a model that can identify the creditworthiness of borrowers.

## Written Analysis:
    Machine Learning 1 Model:
  Model 1, trained on the unaltered data, achieves an accuracy of 94.4% in predicting the two labels. The model excels at forecasting healthy loans, boasting precision and recall scores of 1.00. Nonetheless, there is room for improvement in predicting high-risk loans. The precision score for high-risk loans stands at 0.87, implying that only 87% of true high-risk loans were accurately predicted. Additionally, the recall score for high-risk loans is 0.89, indicating that the model identified only 89% of all high-risk loans in the dataset.

    Machine Learning 2 Model:
  Model 2, which was trained on resampled data, achieves a prediction accuracy of 99.6% for the two labels. The model demonstrates excellent performance in predicting healthy loans, with precision and recall scores both reaching 1.00. While the precision score for high-risk loans remains at 0.87, there is an improvement in the recall score to 1.00. This suggests that the model is now capable of accurately predicting all high-risk loans within the dataset.

    Summary
  The analysis overall suggests that Model 2 surpasses Model 1 in forecasting high-risk loans and boasts an overall higher accuracy in predicting both labels. Specifically, Model 2 exhibits a relatively high precision in predicting high-risk loans and successfully identifies all high-risk loans in the dataset, marking a notably strong performance in this context. Therefore, I would advise employing Model 2 for the identification of high-risk loans, given its superior accuracy in label prediction.
