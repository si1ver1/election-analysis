# Election_Analysis

## Overview of Election Audit
We were given the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of Counties who received votes.
3. Calculate the total number of votes each county received.
4. Calculate the percentage of votes each county won.
5. Determine the largest county turnout based on popular vote.
6. Get a complete list of candidates who received votes.
7. Calculate the total number of votes each candidate received.
8. Calculate the percentage of votes each candidate won.
9. Determine the winner of the election based on popular vote.


## Resources
- Data Source: election_results.csv
- Software: Python 3.8.1, Visual Studio Code 1.47.2

## Election-Audit Results
The analysis of the election show that:
- There were "369,711" votes cast in the election.
- The counties were:
    - Jefferson
    - Denver
    - Arapahoe
- The county results were:
- Jefferson received "10.5%" of the vote and "38,855" number of votes.
- Denver received "82.8%" of the vote and "306,055" number of votes.
- Arapahoe received "6.7%" of the vote and "24,801" number of votes.
- The largest county turnout was: Denver
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
- Charles Casper Stockham received "23.0%" of the vote and "85,213" number of votes.
- Diana DeGette received "73.8%" of the vote and "272,892" number of votes.
- Raymon Anthony Doane received "3.1%" of the vote and "11,606" number of votes.
- The winner of the election was:
- Diane DeGette, who received "73.8%" of the vote and "272,892" number of votes.

## Election-Audit Summary
The usefulness of this script goes beyond just the current results. It can be used with data from a new election in the future. There are also some small modifications we can make to the current script to handle variations in those elections:
1. A lot of post election results will show the demographics such as age, race, and gender to try to see if there are any trends. This data would be stored in the same excel sheet along with each ballet number. From there we just need to add new variables and loops to count the extra statistics and then print them out to the console and text file.
2. Voter turnout it another huge statistic to track. In terms of data all we need is the number of eligible voters. From there we can calculate the percentage of actual voters by counting the total number ballets. This could also be used along with point 1 to review voter turn out based on race, age, and other demographics.
