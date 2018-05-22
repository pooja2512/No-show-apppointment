# No-show-apppointment
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

## Overview
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

Key indicators were:
- ScheduledDay tells us on what day the patient set up their appointment.
- Neighborhood indicates the location of the hospital.
- Age = How old is the patient.
- Hipertension = True or False
- Diabetes= True or False
- Alcoholism = True or False
- Handcap = True or False
- SMS_received = 1 or more messages sent to the patient.
- No-show = True or False.
- Scholarship indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
-‘Bolsa Família’ It is a social welfare program of the Brazilian government, part of the Fome Zero network of federal assistance       programs.Bolsa Família provides financial aid to poor Brazilian families

The project involved data assessment and cleaning, performing EDA and drawing conclusions from the data.

### Statistical Analysis
- Examinations of central tendencies and spread
- Data visualization
- One-way ANOVA hypothesis testing
- Correlation and linear regression hypothesis testing

## Technologies Used
- Python, Numpy, Pandas, Matplotlib, Scipy
- Jupyter Notebook

## Key Findings
- Observerd age group of patients in our dataset is from 0 to 80.
- Hypertension is observed more followed by diabetes,Alcoholism,Handicap.
- Senior people (age above 50) are most likely suffering from hypertension and child are most likely handicap.
- More number of female are suffering from Hypertension and diabetes whereas male are more likely to suffering from alcoholism.
- Irrespective of gender 80% of people visit to their scheduled appointments & that's a good sign It shows people do care about their health issues.
- 1% of people in our dataset have received Bolsa Familia scholarship and out of that Middle age group happen to receive highest rate of scholarship
- Parque Industrial,Ilha Do Boi,Aeroporto,Mario Cypreste,Solon Borges are the location of hospitals people most likely visit, Ilhas Oceanicas DE Trindade,Santos Dumont,Santa Cecilia,Santa Clara,Itarare are the location of hospitals people most likely don't visit
- It shows people who haven't received SMS visit on their scheduled appointment so,receiving SMS is not particularly a good parameter to predict if patient will show or not
- What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?
-   Disease,age group,SMS,scholarship,month,weekday are the top paramenters in predicting if patient will show up on the scheduled           appointment.
