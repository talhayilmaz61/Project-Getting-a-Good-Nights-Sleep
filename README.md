# Project-Getting-a-Good-Night's-Sleep
Delve into anonymized sleep data from SleepInc's innovative SleepScope app. I analyzed lifestyle survey data using Python to uncover relationships between exercise, gender, occupation, and sleep quality. This project reveals patterns that provide valuable insights into what influences better sleep, enhancing user wellbeing and engagement.

Tasks:
Which occupation has the lowest average sleep duration? Save this in a string variable called lowest_sleep_occ.

Which occupation has the lowest average sleep quality? Save this in a string variable called lowest_sleep_quality_occ. Did the occupation with the lowest sleep duration also have the lowest sleep quality? If so assign a boolean value to variable same_occ variable, True if it is the same occupation, and False if it isn't.

Let's explore how BMI Category can affect sleep disorder rates. Start by finding what ratio of app users in each BMI Category have been diagnosed with Insomnia. Create a dictionary named: bmi_insomnia_ratios. The key should be the BMI Category as a string, while the value should be the ratio of people in this category with insomnia as a float rounded to two decimal places. 

## 💾 The data: sleep_health_data.csv

SleepInc has provided you with an anonymized dataset of sleep and lifestyle metrics for 374 individuals. This dataset contains average values for each person calculated over the past six months. The data is saved as `sleep_health_data.csv`.

The dataset includes 13 columns covering sleep duration, quality, disorders, exercise, stress, diet, demographics, and other factors related to sleep health. 

| Column | Description |
|---------|----------------------------------------|  
| `Person ID` | An identifier for each individual. |
| `Gender` | The gender of the person (Male/Female). |  
| `Age` | The age of the person in years. |
| `Occupation` | The occupation or profession of the person. |
| `Sleep Duration (hours)` | The average number of hours the person sleeps per day. |
| `Quality of Sleep (scale: 1-10)` | A subjective rating of the quality of sleep, ranging from 1 to 10. |
| `Physical Activity Level (minutes/day)` | The average number of minutes the person engages in physical activity daily. |  
| `Stress Level (scale: 1-10)` | A subjective rating of the stress level experienced by the person, ranging from 1 to 10. |
| `BMI Category` | The BMI category of the person (e.g., Underweight, Normal, Overweight). |
| `Blood Pressure (systolic/diastolic)` | The average blood pressure measurement of the person, indicated as systolic pressure over diastolic pressure. |
| `Heart Rate (bpm)` | The average resting heart rate of the person in beats per minute. |
| `Daily Steps` | The average number of steps the person takes per day. |
| `Sleep Disorder` | The presence or absence of a sleep disorder in the person (None, Insomnia, Sleep Apnea). |
