Cricketers Data Analytics

In this project I have worked on the cricketers data from ESPN website with top Cricketers. https://www.espncricinfo.com/records/highest-career-batting-average-282910 the link is provided to have a look n data.

Steps Followed to the Analytics:----

1. DATA COLLECTION: I collected the data from ESPN CRICK INFO website and load it to the excel sheet to woork on it.
2. DATA CLEANING : After loading the data in to the excel file I saved it to the suitable folder and then after observing the data I worked on cleaning the data by eliminating or filling the missing values. Changing the format of the values from string to integers as the columns like Balls_faced, Strike_rate, 4s, 6s contains the values like 5*, 800+, 89+, 6+. So I removed the extra symbols that were messing up the data.
3. Finding the duplicate entries and eliminating them.
4. Feature Engineering: I created suitable columns from the existing columns so that the future calculations will become easy and sorted. I splitted the TIME SPAN {for which the player played} column to the Rookie year and Final Year respectively. Player Name column contains the country name also So I just splitted them to two columns.
5. I solved analytical question such as
     a. Calculate average career length
     b. Averge batting strike rate for cricketers who played for more than 10 years
     c. Find number of cricketers who played before 1960
     d. Max Highest inn scores by country
     e. Hundreds, Fifties, Duck(0) avg By country
   ![image](https://github.com/sakshi721/Price-predictor/assets/58660443/16f23ae1-7118-4560-b867-ef980696ed55)
