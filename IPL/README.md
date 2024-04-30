# IPL Live Score Dashboard 
![Home Page](https://github.com/yaswanth144/Power-BI-Projects/assets/54733845/5ed0b9cc-b600-47e2-ac8b-8c3cd89e7117)
![Live Score](https://github.com/yaswanth144/Power-BI-Projects/assets/54733845/7f054d11-731e-4a09-9149-ac7114cbc65f)
![Points Table](https://github.com/yaswanth144/Power-BI-Projects/assets/54733845/cd94f301-8150-4a3b-bd2c-8e8e5d8647ff)

# Data 
Collected live data from RapidAPI website. First we have to create account in rapidApi to use cricbuzz api. After creating account, search for cricbuzz api.
# Power Query Transformations
1. Created three queries for following
   1. first query for getting data from RapidApi website and used as a base query for creating  other two queries.
   2. As mentioned above, first query is used for second query for getting a match Id for getting  Score for that particular match.
   3. Similarly first query is used for creating third query for getting batters and bowlers details along with images of captains.
2. 1. After creating above three queries, convert them into table and then expand columns.
   2. Keep necessary columns and remove unnecessary columns.
   3. Change column names for better understanding.
   4. Finally change datatypes for columns if needed.

# Visualizations
1. For canvas background, created a image in ppt which was shared in this repository. I have used the same image as background for all the three pages Home page,Live Score page and Points Table page.
2. Live page dashboard consists of both innings bowling and batting scorecards.
3. Scorecards includes scores,runrate,bowling and batting performances of players of both the teams.
4. Points Table page consists of all teams in points table and it gets updated after every match once we refresh PowerBI.
