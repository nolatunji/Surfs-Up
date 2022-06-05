# surfs-up
![istockphoto-1296277228-612x612](https://user-images.githubusercontent.com/96552268/172037988-0a9419af-cf2a-47df-841d-197c16a0edb5.jpg)

## Overview
Our business partner W. Avy has asked for an analysis of weather data on the island of Oahu - the proposed location for a future surf and ice cream shop we would like to open. He wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. For this project I used SQLite, Jupyter Notebook, and VS Code.

## Results
For the analysis the weather dataset needed to first be filtered using SQLite queries to retrieve the temperatures for the months of June and December and put into lists. 

### June List
![June List ](https://user-images.githubusercontent.com/96552268/172037387-743a9934-1c69-4759-ac77-166fa83b7151.png)
### Dec List
![Dec List](https://user-images.githubusercontent.com/96552268/172037389-dad762e7-b36f-4361-841d-0d048b4bd412.png)

Using the filtered data two dataframes were created from the lists for June and December. In order to get the best overview of the Oahu weather during the months of June and December the summary statistics were calculated for each dataframe using the describe() method as portrayed in the images below. 

![June DataFrame](https://user-images.githubusercontent.com/96552268/172037645-47d368ae-d937-4e33-8372-0c47d94c5035.png) ![Dec DataFrame](https://user-images.githubusercontent.com/96552268/172037647-f4268afd-d5da-4c79-8fb3-2ac26e973277.png)


![June Summary](https://user-images.githubusercontent.com/96552268/172037666-d8d23602-0d17-4745-9783-f2e5f079f03d.png)
![Dec Summary](https://user-images.githubusercontent.com/96552268/172037668-0fcc2012-e04a-454e-9e34-5060e42740f2.png)



## Summary 
Based on the analysis Oahu appears to be a good location for the surf and ice cream shop. The avergage temperature for June is 78 degrees and only drops to an average temperature of 71 degrees in December. This is a good indication that the temperature stays stable throughout the year and does not drop drastically in the colder months which is ideal for the this type of business. 
