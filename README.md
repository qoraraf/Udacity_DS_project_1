# Udacity_DS_project_1
First project in my udacity-misk Data Science nano-degree: Blog post

Traffic accidents in Saudi Arabia have become one of the main problems the kingdom is dealing with. With this project I try to look at the number of children involved in those accidents and find out when and where their percentage is lower.

   - What is the total number of accidents per month?
   - What is the percentage of children that are involved in these accidents per month?
   - What is the the percentage of children involved for each region during the whole year?
   - Comparing the largest regions in the kingdom of Saudi Arabia, where is the highest percentage of children involvement into traffic accidents?

<img src="https://cdn-images-1.medium.com/max/2000/1*nz-xbNsB8b5pmJabS6VnJQ.png">

<b>Files included:</b>

- traffic-accident-statistics-as-of-1439-h.xls (data file in Excel format). It contains 17 sheets with the same number of columns and same headers. I have concatenated them to one dataframe in pandas.<br>
    The data is provided by the Ministry of Interior - General Directorate of Traffic<br>
    
- traffic_KSA.ipynb (Jupyter notebook using Python 3.8, and common libraries).<br>

<b>Installed modules to produce the jupyter notebook:</b>

- pandas
- matplotlib
- numpy
- ploty
- plotly express
- seaborn

 <b>Acknoledgement:</b>
 
The data I have used was sent to me from my mentor Mr. Haroon. I highly appreciate his help. <br>
The data can be found on the Saudi portal for Open Data at:<br>
https://data.gov.sa/Data/en/dataset/traffic-accident-statistics-as-of-1439-h 


<b>Key Steps for Project</b>

Following the CRISP-DM process in finding solutions

1) I have used the traffic accidents data in KSA for the year 1439 Hijri calendar.

2) My business questions are:
    - What is the total number of accidents per month?
    - What is the percentage of children that are involved in these accidents per month?
    - What is the the percentage of children involved for each region during the whole year?
    - Comparing the largest regions in the kingdom of Saudi Arabia, where is the highest percentage of children involvement into traffic accidents?

3) I have created a Jupyter Notebook to explore and analyse the data:

    Preparing the data:

      - Read all sheets in the excel workbook and combine them.  
      - Clean data, rename columns, and change the arabic naming of months to english words.<br>  
      - Create a dataframe for the data containing the age categories.<br>  
      - Provide visualized answers for my business questions

4) Please go to my blog post, where I present my insights:<br>
    https://medium.com/@fatsammar/traffic-accidents-analysis-in-saudi-arabia-during-1939-hijri-df581248c1d4
