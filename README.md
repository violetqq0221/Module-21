** Self-Assesment
I was working on machine learning model and python for this project. I am getting into machine learning model during the class. After we selected the topic, I would like to know how much CO2 emission we will produce in the future and can we possible meet the Paris agreement. Therefore I participate the machine learning part for our final project. 
I tried to use the linear regration to predict future amount. After we finish the linear regression model, we would like to know  about which country are the higher CO2 emitter. I used the unsupervised clustering machine learning by finiding k means from elbow curve. Then initialize and fit the model. By using the hvplot, I can see the clustering countries result. 
The result shows initially, the high emitters are most European countries and the US, later on, after the 2000s, more developing countries like China and India became bigger emitters.

Since the last module we learned from the class was neural networks. As we learnind from the class, neural networks which works for the large dataset, we wanted to explore deep neural networks to see if it's a good fit for our dataset.
 
However after fiting the model, we got the accuracy 0 initially. This result is not as we expected. we discussed and tried to understand the problem. Our dataset is continuous, the model loss function we had used was "binary cross-entropy", it is meant for classification problems, not for regression. We did additional research to try to overcome this problem, we switch the loss function to "mean square error" to again perform the training.
This time, we see that the model was able to reduced the loss and improved the accuracy after training. Although the result of mean square error are high, after do more resarch and discussion with my group menber. We found that the deep neural network is not good fit for our dataset due to continuous data. For our dataset, the best fit models are liner regression predict for future CO2 emission and unsupervised learning to cluster countries by emissin amount.

Our group always have additional zoom meeting to discuss our progress, also we using the slack to chat if we have problem when we work our own part. I always give some suggestions or serach some useful through Internet. 


**Project and Team Summary

Our group communication with slack, email and zoom. Although our group members are all from different time zone and everyone with heavy workload. We still try to find the extra time to meet on Zoom and discuss the project. When we start this team, we even didn't have topic yet and didn't know what kind of database we would like to analyze. After discussion we settle to CO2 emission topic and looking for the dataset to start our project. 

Our Topic is Analysis of CO2 Emissions Impacting Climate Change, the dataset was obtained from Kaggle and was provided by CICERO Center for International Climate Research.
The dataset contained total CO2 Emissions (MtCO2) from coal, oil, gas, cement, flaring, other sources, and per capita with more than 60,000 rows of data collected from 1750 to 2022.
We use linear regression to predit the future amount of global CO2 to see can we meet the Paris agreement or not. We use the unsupervised unlable learning to cluster the simiar CO2 amount of emitter. The result shows initially, the high emitters are most European countries and the US, later on, after the 2000s, more developing countries like China and India became bigger emitters.
The final model we tried was neural networks. Since our dataset is continuous dataset, we couldn't use accuracy to predict our model, we use the " mean square error" to predict our model later on. We tried to tune with different neurons, hidden layer and train with number of epochs. We are able to observe model loss and accuracy. Although the result is high on "mean square error". 
We discussed and tried to understand the problem. Our dataset is continuous, the model loss function we had used was "binary cross-entropy",it is meant for classification problems, not for regression.It mean our dataset is not the good fit for neuro network model.  
The conclusion of our machine learning is that linear regression is the best method to prediect for future CO2 emission, and also unsupervised learning is able to cluster countries by their emission amount. 
 
