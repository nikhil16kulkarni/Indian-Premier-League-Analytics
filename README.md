# Indian-Premier-League-Analytics

This project aims to perform analytics on cricket data to gain insights into team performance, player analysis, match results, and other related aspects of the game. It involves analyzing a cricket dataset with various columns such as match details, teams, players, venues, toss decisions, match results, and more. It also predicts the winning team when the necessary information such as oppenent team, venue, toss winning team and toss decision are provided.

### Dataset Source

The cricket dataset used in this project is sourced from Kaggle. The specific dataset used is the "IPL Complete Dataset 2008-2020" by PatrickB1912. The dataset can be found at the following link:

[IPL Complete Dataset 2008-2020](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020?select=IPL+Matches+2008-2020.csv)

The dataset used for this project is in CSV format and contains the following columns:

id: Unique Match ID as per ESPNCricinfo<br />
city: City where the match was played<br />
date: Date of the match<br />
player_of_match: Player of the Match<br />
venue: Venue of the match<br />
neutral_venue: Indicates whether the venue is neutral or not<br />
team1: Team 1<br />
team2: Team 2<br />
toss_winner: Team that won the toss<br />
toss_decision: Toss decision (batting or bowling)<br />
winner: Match winner<br />
result: Match result<br />
result_margin: Margin of win<br />
eliminator: Indicates if the match had a super over<br />
method: Indicates if Duckworth-Lewis method was applied<br />
umpire1: First umpire<br />
umpire2: Second umpire<br />


### Project Goals
The main objectives of this project are as follows:

*Team Performance Analysis:* Analyze team performance, win-loss ratios, performance in different venues, and identify trends over time.<br /><br />
*Player Performance Analysis:* Determine the most consistent or impactful players based on the number of "Player of the Match" awards, analyze performance against specific teams/venues/conditions, and calculate relevant statistics.<br /><br />
*Toss Analysis:* Analyze the correlation between winning the toss and winning the match, determine the most preferred toss decision, and identify teams with higher success rates after winning/losing the toss.<br /><br />
*Match Result Analysis:* Analyze the distribution of match results, identify common result types, and study the impact of match conditions/factors on the outcome.<br /><br />
*Venue Analysis:* Identify venues where teams perform exceptionally well or struggle, analyze average scores/run rates at different venues, and determine the impact of venue conditions on match outcomes.<br /><br />
*Data Visualization:* Create visualizations such as charts, graphs, and heatmaps to represent statistical insights and trends.<br /><br />


### Setup and Dependencies
To run this project, ensure you have the following dependencies installed:

Python (version 3.0 or above)<br />
pandas<br />
matplotlib<br />
scikit-learn<br />

### Usage

Clone this repository to your local machine or download the project files.<br />
Place the cricket dataset file (in CSV format) in the project directory.<br />
Update the file path and other configuration details in the project code as required.<br />
Run the Python scripts to perform various analytics tasks on the cricket dataset.<br />
Modify the code or add additional functionality based on your specific requirements.<br />


### Results and Outputs
The project provides various outputs and visualizations based on the performed analytics tasks. These include:

Team performance metrics such as win-loss ratios, performance by city/venue, and trends over time.<br />
Player performance analysis, including the most consistent or impactful players, performance against specific teams/venues/conditions, and calculated statistics.<br />
Toss analysis results, correlation between winning the toss and winning the match, preferred toss decisions, and success rates after winning/losing the toss.<br />
Match result analysis, distribution of match results, common result types, and impact of match conditions/factors on the outcome.<br />
Venue analysis<br />

***One of the key functionalities of this cricket analytics project is the ability to predict the likely winner of a match given two teams. This prediction is based on machine learning techniques applied to historical cricket data.***
