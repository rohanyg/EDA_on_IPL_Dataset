# EDA_on_IPL_Dataset
Conducted Exploratory Data Analysis on the Indian Premier League dataset using Python, identifying the most successful teams, players and key factors influencing wins or losses. Provided actionable recommendations for teams and suggested players a company should endorse to its products. Helped in enhancing decision-making processes through data-driven insights.

## Table of Contents
- [Project Overview](#project-overview)
- [Business Task](#business-task)
- [Data Sources](#data-sources)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Key Findings](#key-findings)
- [Limitations](#limitations)

### Project Overview
In this project, I performed Exploratory Data Analysis on the Indian Premier League dataset using Python. Utilized python libraries such as pandas and matplotlib. My work involved data cleaning, transforming the data and creating visualizations. Performed analysis on team performance, player statistics and match outcomes. Through this analysis, I identified the most successful teams, standout players and key factors influencing wins or losses. I provided actionable recommendations for teams and suggested specific players for product endorsements. This analysis enhanced decision-making processes and offered valuable insights for strategic planning in sports marketing.

### Business Task
To perform the Exploratory data analysis on the Indian Premier league dataset. As the sports analyst find out the most successful teams , players and factors contributing the win or loss of the team. To suggest the teams or players a company should endorse to its products.

### Data Sources
IPL Data: The primary datasets used for this analysis are "matches.csv" and "deliveries.csv" files, containing 12 years detailed information about IPL matches and each deliveries.

### Data Cleaning/Preparation
In the initial data preparation phase, several tasks were performed to ensure accurate analysis:
- Handled null values appropriately.
- Removed irrelevant columns.
- Created derived dataframe for better analysis.

![IPL_img](https://github.com/rohanyg/EDA_on_IPL_Dataset/assets/136742005/5eb95369-d611-4bd5-b1fe-2873e5e251c6)

### Exploratory Data Analysis
Conducted analysis on various aspects of IPL data such as matches ,toss, batting, bowling, fielding and venue. Explored the Correlation between these aspects. Utilized visualizations like bar charts and piechart to represent findings effectively. 

Matches Analysis:
- Recognized players with the most Player of the Match awards.
- Identified teams with the most matches played in a season.
- Analyzed highest scoring matches and matches decided by a Super Over.
- Calculated total matches played by city and total matches played by each team.
  
Team Analysis:
- Recognized the team with the highest number of IPL wins.
- Calculated Win Percentage and analyzed teams with the most titles won.
- Identified matches with the maximum win margin.
  
Toss Analysis:
- Analyzed toss-winning percentages for teams.
- Studied outcomes based on toss decisions (fielding/batting first).
- Investigated match results concerning the team that won the toss.
  
Batting Analysis:
- Identified the top batsmen by total runs, strike rate, average and boundary percentage.
- Calculated Boundaries Percentage and recognized players with the highest individual scores.
- Analyzed number of centuries and fifties scored by players.
- Studied the number of boundaries, sixes, and fours hit by players.
  
Bowling Analysis:
- Identified the top bowlers by wickets, strike rates, averages,dotball percentage and economy rates.
  
Season 2019 Analysis:
- Conducted analysis on above mentioned KPIs separately for 2019 season to understand players who performed good throughout IPL is also performing good in this last season.
  
Factors Influencing Win:

- Toss Win and Match Victory
- Highest Individual Score Contributing to Team Win
- Centuries Scored Leading to Team Victory
- Team Fielded First and Won
- Team Batted First and Won
- Home Win Percentage
  
Venue Analysis:
- Explored top venues hosting matches.


### Key Findings

Most succesful teams which have consistently performed well over the years winning multiple titles:
-  Mumbai Indians
-  Chennai Super Kings
-  Kolkata Knight Riders
  
Most Succesful Players with good statistics in IPL History:

- Virat Kohli
- AB de Villiers
- Chris Gayle
- MS Dhoni
- SK Raina
- DA Warner
- RG Sharma
- SL Malinga
- Harbhajan Singh
- RA Jadeja
- AD Russell
- PP Chawla
- SP Narine
- B Kumar
- DW Steyn
- GJ Maxwell
- SR Watson
- Bravo

In Last Season 2019: 
- RR pant
- JC Buttler
- Imran Tahir
- K Rabada
- HH pandya

These players have excelled on the field and also have a strong online presence, making them prime candidates for endorsements.

- When these players performed well, the team invariably clinched victory.
- Teams winning the toss and choosing to field have a higher success rate in IPL matches.
- The above mentioned factors are significant contributors to the team's victories.
- Certain venues, such as Eden Gardens and Wankhede Stadium have hosted more matches indicating their popularity among organizers.

### Limitations

- Player endorsements might also depend on the player's fan base and popularity, which might not be fully captured in statistical analysis.
- The analysis may be based on historical data, which might not reflect current team or player capabilities accurately.
- While descriptive analysis can identify trends, it might not be sufficient for accurate predictions about future matches or player performances.
- The analysis might not consider external factors like weather conditions, injuries and Pitch conditions which can significantly impact match outcomes.
- Its hard to pick few players because the number of matches played by the players vary and some predefined parameters can make the analysis easier to some extenct.
