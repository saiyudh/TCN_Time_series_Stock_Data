# TCN_Time_series_Stock_Data
TCN_Time_series_Stock_Data


## Goal
The goal of this project is to analyse the prediction capabilities of TCN(Temporal Convulation Network) on the stock dataset compared to RNN,LSTM,CNN.

# Getting Started

## Prerequisites
Jupyter Notebook, Google Colab, Basic knowledge of python and visualization through mathplotlib. 

## Description
Using Time-Series Stock data we are comparing TCN,RNN,LSTM,CNN using macro-average-F1 measure and Accuracy.
A total of 8915 instances over 82 attributes. 
## Implementation
* Data Preprocessing
  * Handled missing values with forward fill and zero fill. 
  * Feature Scaling
  * Data split using Cross validation 80:10:10
* Evalution metrics
  * macro-average-F1
  * Accuracy
            

## Results
The visualization showed TCN and CNN were the top two performers.

## Future Improvements 

* More Randomization
* increase number of epochs 
* make models more complex enough
