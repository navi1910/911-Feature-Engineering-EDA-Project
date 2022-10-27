
# 911-Feature-Engineering-EDA-Project
## Emergency 911 calls Feature Engineering and Exploratory Data Analysis Project
This project aims to analysis calls to 911 (emergency calls) in Montgomery County Pennsylvania, U.S.A.
For this project we will be analyzing some 911 call data from Kaggle. The data contains the following fields:

* lat : String variable, Latitude
- lng: String variable, Longitude
- desc: String variable, Description of the Emergency Call
- zip: String variable, Zipcode
- title: String variable, Title
- timeStamp: String variable, YYYY-MM-DD HH:MM:SS
- twp: String variable, Township
- addr: String variable, Address
- e: String variable, Dummy variable (always 1)

## Methods
- Basic data exploration
- Visualizations
- Feature Engineering

## Technologies used
- Python
- Pandas
- Matplotlib

## Procedure
- The data is downloaded from Kaggle.
- The required modules are imported.
- The data is imported as a Data Frame using pandas.
- The basic information of the data is seen using `info`.
- The data is summarized using `describe`.
- The head of the data is printed.
- Some queries are done in order to understand the data.

### The 911 call reasons are plotted against their Frequencies.
![reasons barplot](https://github.com/navi1910/911-Feature-Engineering-EDA-Project/blob/master/countplot.png 'countplot')

- Feature Engineering is done on the Timestamp.
    - Timestamp is used to obtain Hour of Call.
    - Timestamp is used to obtain day of week of the particular Call.
    - Timestamp is used to obtain Month of Call.

### Countplot is created for Call Reasons according to Day of the Week.
![day of week](https://github.com/navi1910/911-Feature-Engineering-EDA-Project/blob/master/count_dayofweek.png 'day of week')

### Countplot is created for Call Reasons according to Month.
![Month](https://github.com/navi1910/911-Feature-Engineering-EDA-Project/blob/master/count_month.png 'month')

## Contact
https://www.linkedin.com/in/naveen-a-902a671b3/

## Data Source
https://www.kaggle.com/datasets/mchirico/montcoalert

## Credits
https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/learn/lecture/5733408?start=0#overview
