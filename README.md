# Mireille_feudjio_Portofolio 
## Data Scientist | Machine Learning | Managing Data for Better Life

### 1. Classification 

#### [Heart Disease: What is my status?](https://github.com/pascale25/Heart-Disease-Story-Telling/blob/c55f1b481055a5cbed2423afc5791acfd69eed2e/Story_Telling_Heart_Disease/Storry%20Telling%20Heart%20Disease_two.pdf)
Performed multiple classification algorithms using grid search and random search for hyperparameter tuning. 3 models were developed (KNN, Random Forest, XGBOOST). 

![image](https://user-images.githubusercontent.com/90922607/185215488-4e43f569-2b38-40b4-b9c0-8fef9c896ffd.png)
   
#### Keys Output
3 models were developed (KNN, Random Forest, XGBOOST). Form lab exam of the patient, all the models predicted that, the patient has no risk of heart disease. -  We cared about correct prediction, and we have an unbalanced dataset, so f1_score helped to select the best model - Random Forest. 
Person with heart disease is more likely to be:
-	Person with normal resting electrocardiogram. 
-	Person who exercise-induced angina;
-	Person with Asymptomatic chest pain type;
-	Person with fasting blood sugar  > 120 mg/dl (1) ;
-	Female with heart disease tend to have Hight cholesterol than male.
-	mean value of aged person with heart disease is 55.58.
-	mean value of resting blood pressure of person with heart disease is 134.18.
-	mean value of Max heart rate of person with heart disease is 127.65.

[Presentation](https://github.com/pascale25/Heart-Disease-Story-Telling/blob/c55f1b481055a5cbed2423afc5791acfd69eed2e/Story_Telling_Heart_Disease/Storry%20Telling%20Heart%20Disease_two.pdf)

[Report](https://github.com/pascale25/Heart-Disease-Story-Telling/blob/c55f1b481055a5cbed2423afc5791acfd69eed2e/Story_Telling_Heart_Disease/Storry%20Telling%20Heart%20Disease_two.pdf)


###  2. Time Serie analysis 

### [Avocado: what is the expected price and consumption of avocado in 2022? ]( https://github.com/pascale25/Challenges/blob/7839fb3e4c4f409a08443d009c37da8e77d1b31b/Ultimate_challenge/Ultimate_challenge.ipynb)
Avocado price and total volume were forecasted with SARIMAX, ARIMA algorithms.  The mean absolute error (MAE) metric was used to evaluate and select models. MAE was 0.063 for the best model. 
             		
![image](https://user-images.githubusercontent.com/90922607/185219302-0cf0bd56-32c6-4ea7-ac16-8aab96d45d77.png)
#### Weekly trend of avocado prices
![image](https://user-images.githubusercontent.com/90922607/185219712-9f52001f-80a9-42d6-9918-1a0d42811cbf.png)
#### Model Evaluation
![image](https://user-images.githubusercontent.com/90922607/185219652-c60761ff-d7df-4f8c-8319-9641783cf03a.png)
#### Plot of the past, the test and prediction price of Avocado                                                   

#### Keys Output
-	Clear distinction between organic and conventional avocados.
-	The price of the organic avocado is higher than that of the conventional avocado.
-	The total volume of organic avocados sold is less than that of conventional avocados.
-	New York is among the top 5 regions with high price (and high volume) in organic and conventional avocado (occupied 4th or the 5th rang).
-	When total volume increases, price decreases and vice versa.
-	8 models have been developed for each type of avocado (conventional price, conventional volume, organic price, organic volume).
-	The predicted prices of avocados (conventional and organic) are close to real values. 
-	The average of the difference between this value (pred – actual) MAE is 0.063. 

[Data Wrangling](https://github.com/pascale25/Forecasting_Avocado_price_volume/blob/182cf5efd63b4c2c2ba64571a7e26e611cd0abd4/Capstone_project_Forecasting_Avocado_price_volume/Data_wramgling_avocado.ipynb)

[Exploratory Data analysis one](https://github.com/pascale25/Forecasting_Avocado_price_volume/blob/182cf5efd63b4c2c2ba64571a7e26e611cd0abd4/Capstone_project_Forecasting_Avocado_price_volume/Data_wramgling_avocado_EDA_Part_one_all_regions.ipynb)

[Exploratory Data analysis two](https://github.com/pascale25/Forecasting_Avocado_price_volume/blob/182cf5efd63b4c2c2ba64571a7e26e611cd0abd4/Capstone_project_Forecasting_Avocado_price_volume/Data_wramgling_avocado_EDA_Part_Two_New_york.ipynb)

[Modeling one](https://github.com/pascale25/Forecasting_Avocado_price_volume/blob/182cf5efd63b4c2c2ba64571a7e26e611cd0abd4/Capstone_project_Forecasting_Avocado_price_volume/Forcasting_Avocado_NY_con_price_V.ipynb)
[Modeling two](https://github.com/pascale25/Forecasting_Avocado_price_volume/blob/182cf5efd63b4c2c2ba64571a7e26e611cd0abd4/Capstone_project_Forecasting_Avocado_price_volume/Forcasting_Avocado_NY_con_volume_V.ipynb)

[Modeling three](https://github.com/pascale25/Forecasting_Avocado_price_volume/blob/182cf5efd63b4c2c2ba64571a7e26e611cd0abd4/Capstone_project_Forecasting_Avocado_price_volume/Forcasting_Avocado_NY_org_price_V.ipynb)

[Modeling four](https://github.com/pascale25/Forecasting_Avocado_price_volume/blob/182cf5efd63b4c2c2ba64571a7e26e611cd0abd4/Capstone_project_Forecasting_Avocado_price_volume/Forcasting_Avocado_NY_org_volume_V.ipynb)

[Report](https://github.com/pascale25/Forecasting_Avocado_price_volume/blob/182cf5efd63b4c2c2ba64571a7e26e611cd0abd4/Avocado_report_final.pdf)

[Presentation](https://github.com/pascale25/Forecasting_Avocado_price_volume/blob/182cf5efd63b4c2c2ba64571a7e26e611cd0abd4/Avocado%20Project%20Presentation%20%5BMireille%20P.%20Feudjio%5D.pdf)

 
### 3. Regression 

#### [Life expectancy. Does immunization matter?](https://github.com/pascale25/Life_expentancy_project/blob/e06794d16153fe44c951d6d4c52e07d6954e32b4/Life_expectancy_final_report_2022/Life_expectancy_final_report/reports/Life_expectancy_project%5BMireille%20P.%20%20Feudjio%5D.pdf)
14 regression models have been developed to predict life expectancy, the chosen one is Gradient boost with MAE of 0.202 on train set and 1.431 on the test set, R square is 0.94 on the test set. 

![image](https://user-images.githubusercontent.com/90922607/185222187-2d2d0bf9-e954-47f4-bc15-3debe05b3f64.png)
#### Assessment and treatment of missing value (if not, 69% of data will be drop).
![image](https://user-images.githubusercontent.com/90922607/185223420-210a74ec-2a9c-4a6c-a59f-fb3e26ef4b83.png)
#### Check the normal distribution of the data
![image](https://user-images.githubusercontent.com/90922607/185224272-da0bcedb-bebb-4107-ab78-03f9414cda85.png)
#### MAE of tree based model and linear model

#### Keys Output
-	Life expectancy has increased over years.
-	The mean average of the life expectancy of developed countries is generally higher compared to  that of developing countries
-	However, the ratio of LE over the decade of 2005 to 2015 showed that life expectancy in developing countries has greatly increased 
-	Immunization has impacted the improvement of life expectancy and  the reduction of infant deaths.
-	Feature of importance reveals that immunization features has a very low contribution in the model .
-	Economic factors  and mortality factors play an important role in the system.
-	(14) regression models have been developed to predict life expectancy.
-	the chosen one is Gradient boost with MAE of 0.18 on train set and 1.15 on the test set.
 
[Data Wrangling](https://github.com/pascale25/Life_expentancy_project/blob/11508a06c553394122de1c940ed512444be98a3e/Life_expectancy_final_report_2022/Life_expectancy_final_report/Capstone_two_Life_expectancy-Data_wrangling.ipynb)

[Exploratory Data analysis](https://github.com/pascale25/Life_expentancy_project/blob/11508a06c553394122de1c940ed512444be98a3e/Life_expectancy_final_report_2022/Life_expectancy_final_report/Exploratory_Data_Analysis_life_expectancy.ipynb)

[Statistic](https://github.com/pascale25/Life_expentancy_project/blob/11508a06c553394122de1c940ed512444be98a3e/Inferential_statistic_life_expectancy.ipynb)
[Modeling](https://github.com/pascale25/Life_expentancy_project/blob/11508a06c553394122de1c940ed512444be98a3e/Life_expectancy_final_report_2022/Life_expectancy_final_report/Modeling_V3_life_expectancy.ipynb)

[Report](https://github.com/pascale25/Life_expentancy_project/blob/11508a06c553394122de1c940ed512444be98a3e/Life_expectancy_final_report_2022/Life_expectancy_final_report/reports/LIFE%20EXPECTANCY_F.pdf)

[Presentation](https://github.com/pascale25/Life_expentancy_project/blob/11508a06c553394122de1c940ed512444be98a3e/Life_expectancy_final_report_2022/Life_expectancy_final_report/reports/Life_expectancy_project%5BMireille%20P.%20%20Feudjio%5D.pdf)

 
 
### 4. Natural Language processing Playground

This project aims at exploring different concepts of NLP with a movie_ tv_show dataset. We explored issues like the most important genres, the spread of added movies and tv_shows across years and months, recommendation, and apply classification algorithms on the text description dataset.   
![image](https://user-images.githubusercontent.com/90922607/185226365-3afed0c5-5d58-445c-98c3-d82d52d81f8e.png)
![image](https://user-images.githubusercontent.com/90922607/185226428-16823f80-7f11-43fa-b2b3-bc0591aa0d20.png)

 
The notebook investigated concepts like: removing punctuation, tokenize, lemmatize, stemming, stop words,  Create dictionary of the most frequent words and Word Cloud, Gensim and spacy libraries, apply Recommender system, use of Bag of words (unigram, bigram, …), exploring different models (random forest, gradient boost, Naïve Bayes) with vectorized data made with count vectorizer, TFIDF, analyzing similarity between reviews description  and Classification with kmean clustering with the use of Elbow method. 

[notebook](https://github.com/pascale25/NLP_PlayGround/blob/c6d59dbfdb09ce6495edb347f05beb16d2d1e20f/NLP_PlayGround_project/Netflix_NLP_02.ipynb)
 
### 5. Research (statistic, GIS)
#### [Drivers and levers options of shifting cultivation project ](http://pubs.sciepub.com/wjar/5/4/4/index.html)
Define and carry on the  project  to identify drivers motivating farmers to practice shifting cultivation. Developed data collection tools, gathered data with CSPro, analyzed data with R, SPSS, and Excel.  Analyzed and mapped the different trajectories of shifting cultivation practice across three landscapes with QGIS, and ArcGIS. 

[Presentation](https://drive.google.com/file/d/1efooBUDom7VIFqGQdPYl3pdeOVF2XRhZ/view?usp=sharing)

![image](https://user-images.githubusercontent.com/90922607/185227128-fe895393-eef9-4fc7-b3ce-9cb105cb8f40.png)
#### Weight of technical drivers across 3 cities 


![image](https://user-images.githubusercontent.com/90922607/185227019-857df906-2a32-46e3-913c-9f876b954c5a.png)
#### Land cover change and land use change 

### 6. Other projects on Notebook
[SQL](https://github.com/pascale25/Sprinboard_Projects/blob/0179373d59ace977f0fc6f0fe8c614cd8d3ff169/SQL/SQL_Mireille)
[Sqlite3](https://github.com/pascale25/Sprinboard_Projects/blob/0179373d59ace977f0fc6f0fe8c614cd8d3ff169/SQL/SQL_Mireille.ipynb)
[Unsupervised_learning](https://github.com/pascale25/Sprinboard_Projects/blob/0179373d59ace977f0fc6f0fe8c614cd8d3ff169/Clustering%20Case%20Study%20-%20Customer%20Segmentation%20with%20K-Means%20-%20Tier%203.ipynb)
[A/B testing](https://github.com/pascale25/Sprinboard_Projects/blob/0179373d59ace977f0fc6f0fe8c614cd8d3ff169/Frequentist_inference_case_Study/Frequentist%20Inference%20Case%20Study%20-%20Part%20B%20(2).ipynb)
[Classification_project](https://github.com/pascale25/Challenges/blob/7839fb3e4c4f409a08443d009c37da8e77d1b31b/Ultimate_challenge/Ultimate_challenge.ipynb)

