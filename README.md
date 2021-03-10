# IPL-2020-Player-Performance
Predicting the performance score of each player in IPL 2020, where i have done data wrangling , feature engineering and applied different mechine learning algarithams 


Fantasy sports in this age of technology has been a closely connected part of every particular sport community. This time we are trying to predict the player performance index of each player who participated in IPL 2020 using the delivery-by-delivery data of each ball bowled since IPL 2008 till IPL 2019

Datasets :)

"Training.csv" : File Containing various performance stats of a player in a match

"Matches IPL 2020.csv" : Schedule of matches that occrued in IPL 2020

"IPL 2020 Squads.csv" : Squads of each participating club/team in IPL 2020

"Matches IPL 2008-2019.csv" : Schedule of matches that occrued in IPL 2020

"sample_submission.csv" : Sample file. The submission file should be in this format and structure only with the values changed with those predicted ones. Please note that the player names in this file are lexographically order and this order has to be maintained in the submission file also.


What i have Done? :)

created new features like " team1 " and " team2 " from datasets given 

from these created features i derived another feature " team " for every individual player 

also wrangled another feature called " Season " for every match 


sucessfully implimented Pipeline with following models

applied different mechine learning models :

LineaarRegression

DecisionTreeRegressor

RandomForestRegressor

StackingRegressor

xgboostRegressor

xgboost with optuna

compared all models on the basis of RMSE error metrics

finally predicted the predictions with the best model 
