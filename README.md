# Election_Analysis with Python

### 1. Overview of Election Audit:

For this project, I was in charge of an election audit for the Colorado Board of Elections using the dataset, [election_results.csv](https://github.com/mquimi/Election_Analysis/blob/main/Resources/"Resources/election_results.csv"). With the help of python, I was able to write the script and perform the following tasks for the analysis:

* Total number of votes
* A complete list of candidates who received votes
* Total number of votes each candidate received
* Percentage of votes each candidate won
* The winner of the election based on popular vote
* The voter turnout for each county
* The percentage of votes from each county out of the total count
* The county with the highest turnout


### 2. Election-Audit Results: 

1. How many votes were cast in this congressional election?

![alt text](https://github.com/mquimi/Election_Analysis/blob/main/Images/Congressional%20election.png)

2. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

![alt text](https://github.com/mquimi/Election_Analysis/blob/main/Images/County%20Votes.png)

3. Which county had the largest number of votes?

![alt text](https://github.com/mquimi/Election_Analysis/blob/main/Images/largest%20county.png)

Denver was the county with the largest number of votes.

4. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

![alt text](https://github.com/mquimi/Election_Analysis/blob/main/Images/percentage.png)

5. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

![alt text](https://github.com/mquimi/Election_Analysis/blob/main/Images/winner.png)

From the image above, you can conclude that the winner of the election is Diana DeGette with a total of 272,892 vote counts and a winning pecentage of 73.8%

### 3. Election-Audit Summary: 

After creating the python script for the election, I realize that this script is not a one time script and can be modified to meet the criterias that others may want. At the moment, the current script iterates through each row, while reading through the second and third column, allowing users to see the printed results of the total amount of votes, who the winner was, what was the largest county and other useful information that can help determine other analysis. 

Two modifications that can be done with this current script are to:

1. Analyze data on a larger scale: using a county list allowed us to analyze a small scope of counties. With the current script, we can easily modify the dataset with a list of countires or states. Looking at results from a bigger region can help us track other types of election such as primary or electorial.


2. Cadidates's demographics: Knowing the demographics of a person can help provide an understanding of who that person is and make strategic decisions based on what they know. Adding the candidates's deographics will be essential for voters to know who they are electing and what the candidates plan and purpose is. Sad,but true, knowing the candidate age, sex, and ethnic background holds a lot of weight for voters and their decisions. 

