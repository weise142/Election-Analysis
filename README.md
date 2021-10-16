# Election-Analysis
## Project Overview
A Colorado Board of Election employee assigned me the following taks to complete an election audit of a recent local congressional election.
  1. Calculate the total number of votes cast
  2. Create a complete list of candidates who received votes
  3. Calculate the total number of votes for each congressional candidate
  4. Calculate the percentage of votes for each congressional candidate
  5. Establish the election of the congressional election based on the popular vote
  6. Calculate the turnout of voters per county
  7. Calculate the percentage of voters per county based on the total number of votes
  8. Establish the county with the highest voter turnout

## Programs Used
- Data Source: election_results.csv
- Software: Python 3.7.6, VS Code 1.60.2

## Summary
  Total Votes: 369,711
  ### Candidates
  Charles Casper Stockham
  Diana DeGette
  Raymon Anthony Doane
  ### Candidate Results
  Charles Casper Stockham received 23.0% of the votes or 85,213 votes 
  Diana DeGette received 73.8% of the votes or 272,892 votes
  Raymon Anthony Doane received 3.1% of the votes or 11,606 votes
  ### The Congressional Election Winner was
  Diana Degette, who received 73.8% of the votes or 272,892 votes
  ### Voter Turnout per County
  Jefferson generated 10.5% of voters or 38,855 votes
  Denver generated 82.8% of voters or 306,055 votes
  Arapahoe generated 6.7% of voters or 24,801 votes
  ### County with the largest voter turnout
  Denver County had the largest voter turnout generating 82.8% of voters or 306,055 votes
![This is an image](https://github.com/weise142/Election-Analysis/blob/main/Election%20Results.png)
## Election Audit Summary
Creating this election audit including both the candidate outcomes and county information is important because the code can be customized in different ways to help both candidates and election officials. 

In modifying this code, election officials could do a deeper dive into vote counts for both counties, cities, or polling places. This would allow the election officials the ability to determine where resources may need to be allocated for things like better vote counting if there are counties with higher error rates in vote counts for finalized elections. This can be done by bringing this data in using another CSV document, adding additional variables for audited vote count, then writing another if statement to display results if the percentage exceeds a desigated amount or even difference in vote counts exceeds a designated amount. Election officials could also add another variable for polling places per county and then calculating the number of voters per polling place to determine if there is a need for additional polling places. This would be another for loop and if statement to add polling places and calculate number of voters per county. This would allow election officials more data on how to properly allocate budget or resources to make sure each voter has the ability to make their vote count.

This code could also be modified to audit federal elections. Counties could be changed to states or you could write in code to add both states and counties within each state so candidates could use this information to better allocate their resources in an attempt to garner support for their campaign. If we were to add counties within states for a federal election we would need to write a for loop within a for loop to best illustrate where candidates should focus their efforts. 

This code can be used or modified in many ways so election officials better understand their voters. They could also gather additional data points, input them, and modify the code to get more granular with their analysis if wanted or needed meaning this base code could be a valuable resource for the election board.
