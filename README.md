🏆 ICC Men's Cricket World Cup 2023 Analysis
📖 Project Overview
This project presents a comprehensive data analysis of the ICC Men’s Cricket World Cup 2023, performed using Python to uncover key insights into team and player performances.

The objective was to analyze real match data, identify performance trends, understand venue-specific conditions, and visualize the results for better decision-making and presentation to stakeholders.

🎯 Objectives
The analysis aimed to answer the following questions:

Who were the top performers (batsmen and bowlers) across matches?
Which stadiums favored batting or bowling first?
What patterns emerged in match outcomes (won by runs or wickets)?
Which players and teams consistently influenced victories?
⚙️ Tools & Technologies
Category	Tools Used
Programming	Python (Pandas, NumPy)
Visualization	Matplotlib, Plotly
Data Storage & Querying	MySQL
Data Cleaning	Excel
Environment	Google Colab
Reporting	python-pptx (for automated PowerPoint generation)
🧹 Data Preparation
Data Loading & Inspection:
Loaded World-Cup-2023-Schedule.csv for initial review and validation.

Data Cleaning:

Removed duplicates and missing values.
Corrected inconsistent column names and data types.
Formatted date and numeric fields properly.
Data Integrity:
Ensured the dataset was clean, reliable, and consistent before analysis.

📊 Exploratory Data Analysis (EDA)
Performed a series of analytical steps using Pandas, Matplotlib, and Plotly:

1️⃣ Top Performers
Identified the best scorer and best bowler in each match.
Daryl Mitchell emerged as the best scorer in 3 matches, while Adam Zampa was the best bowler in 5 matches.
2️⃣ Stadium Insights
Analyzed match outcomes by venue.
Wankhede Stadium favored batting first.
Ekana Stadium favored bowling first.
3️⃣ Player of the Match (MoM) Analysis
Travis Head and Mohammad Shami each won 3 MoM awards.
All-rounders and batsmen were the most frequent MoM winners (15 each).
4️⃣ Team Performance
Australia’s all-rounders won 6 MoM awards.
India’s batsmen won 5 MoM awards.
Venue-specific insights:
Kolkata: favored all-rounders (3 MoM awards)
Bengaluru: favored batsmen (3 MoM awards)
5️⃣ Match Outcomes
India: 5 wins by runs, 5 wins by wickets.
Australia: 4 wins by runs, 5 wins by wickets.
📈 Key Visualizations
Top Run-Scorers and Wicket-Takers
Player of the Match Distribution by Role
Stadium Advantage (Batting First vs Bowling First)
Match Outcome Trends (Runs vs Wickets)
All visuals were exported as PNG charts for reporting and stakeholder presentations.

🧩 Insights & Recommendations
Venue Strategy:
Teams should adjust batting/bowling strategies based on venue tendencies.

Player Focus:
All-rounders are key impact players — balance selection around them.

Game Planning:
Plan better for defending and chasing scores based on past win patterns.

Performance Prediction:
Use data patterns to forecast high-impact players and match results.

💼 Stakeholder Presentation
An automated PowerPoint report was generated using python-pptx, containing:

Executive summary
Charts and visual insights
Actionable recommendations
File Output: WorldCup2023_Stakeholder_Presentation.pptx
