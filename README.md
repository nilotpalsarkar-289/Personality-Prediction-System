# Introduction
The project uses machine learning algorithms and advanced data mining concepts to mine a user's characteristics data and learn from it's patterns.
This project will come across areas where it has access to large amounts of behavioral data based on a person. This data can be helpful to classify persons by using Automated personality prediction and classification. There are also areas where there is access to large amounts of person behavioral data. This data can help us to classify persons using automated personality classification.

# Methodology/Concept Used
There are five characteristics of different individuals which are considered commonly known as the big five characteristics namely- openness, neuroticism, conscientiousness, agreeableness and extraversion. These characteristics are stored in a dataset which are being used for training. Based on this training, the personalities of individuals are predicted as well as pre-processed before testing the dataset using the data mining concepts like handling missing values, data discretization, normalisation etc. This pre-processed data can then be used to classify/predict the user's personality based on it's past classifications. <br>
The model which is used to predict the test dataset is “Logistic Regression” as it is an effective model to predict output class labels for dependent categorical data.

# Dataset description
<b>Attribute Description:</b>
No. of attributes are 7 as listed below.

|S.NO |	ATTRIBUTE |	TYPE |RANGE|
| --- | --- | --- | --- |
|1	|Gender	|nominal|	Male / Female|
|2	|Age |	numeric|	17-28|
|3	|Openness	| numeric|	1-8|
|4	|Neuroticism |numeric|	1-8|
|5	|Conscientiousness	|numeric	|1-8|
|6	|Agreeableness	|numeric	|1-8|
|7	|extraversion |	numeric	|1-8|
<br>
<b>Class label description:</b><br>
No. of class labels: 5<br>
Type: Nominal<br>
Values:	
●	Extraverted 
●	Serious 
●	Responsible 
●	Lively 
●	Dependable 