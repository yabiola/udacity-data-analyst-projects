# No Show Appointment - Investigate a dataset
## by Abiola Adeyinka


## Dataset

Scheduling efficiency is most important in every practice especially in the health sector. Its no secret how annoying and discouraging missed appointments can be. A person makes a doctor appointment, receives all the instructions and no-show. Who to blame?

In this project I will be investigating a dataset that contains over 100k patient medical appointments in Brazil hospitals.
The data includes some characteristics about the patients and states whether or not the patient shows up for their appointment.

The orignal dataset can be found here: https://www.kaggle.com/datasets/joniarroba/noshowappointments

Notes:<br>
● ‘ScheduledDay’ tells us on what day the patient set up their appointment.<br>
● ‘Neighborhood’ indicates the location of the hospital.<br>
● ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.<br>
● Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.<br>



## Summary of Findings

1. The age of patients in the dataset is distributed evenly (uniform distribution), there are many young patients in the dataset and the number of patients dropped drastically at age 60. It also shows that we have very vew patients that are very old and above the age of 80.
2. Most of the patients are not alcoholics and very few alcoholics.
3. Most of the patients are not diabetic and those that are more than those that are alcoholic.
4. There are 5 categories of handicap with most of the patients not being handicapped.
5. Most of the patients are not hypertensive but those that are, are more than those that are diabetic and alcoholics.
6. Most of the patients do not have scholarships (not enrolled in Brasilian welfare program Bolsa Família)
7. 20% of patients missed their appointments.
8. Most patients schedule their appointments on Tuesdays and few patients schedule their appointments on Saturdays.
9. Most patients are appointed Wednesdays to visit the hospitals and few patients are appointed Saturday to visit the hospital. No patient is appointed on a Sunday.
10. The graph shows that in each neighbourhood hospital all have more patients that showed up than did not show up. Thats a good sign that no hospital is lacking behind although there is a significant between neighbourhoods that have more patients that the others. <br>
**Conclusion: Neighbourhood does not determine if the patient will show up or not.**
11. The chart for categorical variable does not show any indication of any particular category that has is more important to predict if a patient shows or not shows for their appointment. 
12. The distribution of the age confirms that about 20% of appointments were no-show.
it also shows that most of the patients that came for appointments were babies between 0 - 1 year, then with a fall to normal distribution of patients between 1 - 60 years. The distribution then becomes right skewed from ages 60 and above.
13. Most appointments that were fulfilled were those that had their appointments scheduled in the same day. There was a drastic fall of patient showing onces their waiting days were more than a day.




## Key Insights for Presentation

The data was wrangled before any exploratory analysis was performed. 
After the wrangling and cleaning of the data set. I begun to explore the data by first posing various questions like
 1. What percentage of patients did not show up for their appointment? 
    2. Explore the distribution of appointments across the days of the week. This will help us know what days of the week patients prefer going to the hospitals.
    3. Does the neighbourhood for an appointment determine if a patient will show up or not?
    4. What factors are most important to determine if a patient shows up for an appointment or not? Explore the following dependent variables ('alcholism', 'handicap', 'diabetes', 'hypertension', 'gender', 'scholarship', 'age', 'sms_received') against the no_show variable to determine their relationship to no_show appointments.
    
 Which were used to guide my analysis and provide insights into the data.
