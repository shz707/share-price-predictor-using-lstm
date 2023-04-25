# Share price Predictor
A repository for Share price Predictor project by Shahbaz S, Vishnu M, Dhanush V.


This project uses a LSTM model to analyze the historical closing price of a company's stocks and makes a prediction for its future closing price. 
we have compared the results for each run to predict closing price of stock but ideally our code can be run to predict any column of data set (e.g., High, Low, Volume ..)

# Input Parameters 
Preprocessing and Normalization
	Neural Network Architecture : LSTM 
	Number of Layers (how many layers of nodes in the model; used 3)
	Number of Nodes (how many nodes per layer; used 50)
Training Parameters 
	Training / Test Split : 80 / 20
Batch Size ( kept at 1) 
Optimizer Function 
	MSE and “Adam” Optimizer)
Epochs (kept at 1)
Model Fitting 


# Code
STOCK_PREDICTOR_1_FEATURE.ipynb
Run 1 : feature set = [Closing]    >> Single input 

STOCK_PREDICTOR_2_FEATURES.ipynb
Run 2 : feature set = [Closing, High] >> Highly correlated Columns
Run 3 : feature set = [Closing, Volume] >> Poorly correlated  Columns

# results
we saw that using multiple features improves our average error between predicted and actual value.
Using highly correlated feature set tuples gave us slightly better results

Project synopsis and report has been included.


Enviroment : Google colab  https://colab.research.google.com/

