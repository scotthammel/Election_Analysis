# Election_Analysis

## Overview of Election Audit:
Performing an election audit on a recent local congressional race on behalf of a Colorado Board of Elections employee.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who recieved votes.
3. Get a complete list of counties.
4. Calculate the total number of votes each candidate and county recieved.
5. Calculate the percentage of votes each candidate and county won.
6. Determine the county with largest vote total.
7. Determine the winner of the election based on the popular vote.
    

## Resources 
- Date Source: election_results.csv 
- Software: Python 3.8.5, Visual Code Studio 1.52.1

## Election-Audit Results:
- Total votes: 369,711

- Results from counties:
  - Jefferson recieved 10.5% of the votes and 38,855 number of votes.
  - Denver recieved 82.8% of the votes and 306,055 number of votes.
  - Arapahoe recieved 6.7% of the votes and 24,801 number of votes.

- Denver recieved the largest number of votes with 306,055 (82.8)%

- Candidates:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane

- Results from candidates:
  - Charles Casper Stockham recieved 23.0% of the votes and 85,213 number of votes.
  - Diana DeGette recieved 73.8% of the votes and 272,892 number of votes.
  - Raymon Anthony Doane recieved 3.1% of votes and 11,606 number of votes.

- Winner of the election:
  - Diana DeGette, who recieved 73.8% of the votes and 272,892 number of votes.


## Script Examples:
- Retrieving the vote count and percentage:
<img width="646" alt="c" src="https://user-images.githubusercontent.com/77898345/112768470-d8a46c80-8fe1-11eb-93ff-4ec6d8e25351.png">

- Printing the winning candidate's summary (name, total votes recived and percentage):
<img width="541" alt="Screen Shot 2021-03-28 at 4 13 22 PM" src="https://user-images.githubusercontent.com/77898345/112768523-02f62a00-8fe2-11eb-89a7-6d01e8c226a8.png">




## Election Audit Summary
This script can be applied for future election results. The output would give you the winning candidate based on their votes campared to the total votes. Variables like "county" and candidate" can be switched to get your desired outcome.



