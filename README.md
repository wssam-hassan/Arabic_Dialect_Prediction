# Arabic Dialect Prediction

## About The Project
Many countries speak Arabic. However, each country has its own dialect, so this project aims to build a model using Natural Language Processing to predict the dialect given the text.<br>
Firstly, data is gathered through given api, check [Data Fetching](Data_Fetching.ipynb) notebook.<br>
Secondly, data is cleaned, normalized and preprocessed, check [Data Preprocessing](Data_Preprocessing.ipynb) notebook.<br>
Thirdly, LinearSVC and Bi-LSTM models were built, trained, tested and saved, check [Model Training](Model_Training.ipynb) notebook.<br>
Finally, the best model is deployed through ReSTful API and Graphical User Interfa (GUI), check [Deployment](Deployment.ipynb) notebook.<br>

## Dataset
The dataset were addressed by [Qatar Computing Research Institute](https://www.qf.org.qa/research/qatar-computing-research-institute)

## Results

|   Model       |    F1-Score   |     Accuracy  |
| ------------- | ------------- | ------------- |
|   Bi-LSTM     |      0.458    |     0.506     |
|   LinearSVC   |      0.526    |     0.557     |
