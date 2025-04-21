# Group 7 - Project #2
## Team Name
21482 Group 7
## Team Members
Clay Campbell [@soup_clay](https://github.com/soup-clay)\
Karishma Pandit [@karishmapandit](https://github.com/karishmapandit)\
Anay Patel [@AnayPatek05](https://github.com/AnayPatek05)\
Matthew Schwanekamp [@matthewschwanekamp](https://github.com/matthewschwanekamp)\
Zachary Torres [@ZachTorres](https://github.com/ZachTorres)
## Data Description
Our data set was obtained from [catalog.data.gov](https://catalog.data.gov/dataset/crash-reporting-drivers-data) and contains data about motor vehicle operators involved in traffic accidents on county and local roadways in Montgomery County, Maryland. The columns in the data set contain information about the accident's case number, what kind of accident it was, where it occured, nearby weather and road conditions at the time of the crash, any injuries involved, and details about the cars involved in the crash, and each row represents a unique case.
## 2 Questions and their Importance
### Questions 1
*Does drunk driving or unsafe weather conditions lead to more car accidents, and how do these factors affect accident severity?*

By utilizing data collected about weather conditions and accident severity, civil engineers are better able to design roads with high visibility and are better suited for adverse weather conditions. Also, lawmakers and police forces can use data concerning driver intoxication and accident severity to better understand and cut down on drunk driving accidents. Both of these questions are incredibly important, aimed at reducing car accidents and making our roads safer.
### Question 2
*At what time of day do the highest number of crashes occur?*

By utilizing data/time data with crash volume, police forces are better able to staff appropriately to respond to accidents quickly and get emergency personnel on the scene faster, which is crucial for saving lives in violent accidents. Also, this data can then be used to ask some more causational questions, like why does *this* specific time of day have the highest volume of accidents.
## Data Manipulation
Two calculated fields were created.

In the first visualization, a calculated field was used to define attributes that indicate 'Bad Weather,' defined as foggy or blowing sand, snow, dirt, or soil.

In the second visualization, a calculated field was used to define different parts of the day, i.e., morning, midday, and night. Morning is defined as 5 - 11 am, midday is defined as 12 - 5 pm, and night is 5 pm - 5 am.

## Analysis and Results
### Question 1
Does drunk driving or unsafe weather conditions lead to more car accidents, and how does it affect injury severity?

This visualization shows us that not only are there more collisions when alcohol is involved, but there is also a greater volume and increased severity of injuries in bad weather. Using this data, police departments can utilize more DUI checkpoints to mitigate alcohol contributed instances.

<img width="864" alt="Screenshot 2025-04-18 at 7 42 40 PM" src="https://github.com/user-attachments/assets/d1e452fd-0850-4543-bc2a-7b589442d6ac" />

### Question 2
What time of day do most collisions occur?

This visualization tells us that during midday, there is a higher risk of collisions. This is, in some ways, surprising because one would expect nighttime to have more collisions, where factors could include more under-influence incidents, and seeing can be more challenging at night. Police departments and emergency personnel can then use this data to increase resource allocation to traffic incidents during midday.

<img width="365" alt="Screenshot 2025-04-18 at 7 47 39 PM" src="https://github.com/user-attachments/assets/8b7fba02-e8ed-47bb-85ee-4cb71cefa10a" />

## Tableau Packaged Workbook Link
Link to workbook [MIS4610_Project2]([https://github.com/matthewschwanekamp/TWBFile](https://github.com/matthewschwanekamp/Project2_4610_TWBX/tree/main))
