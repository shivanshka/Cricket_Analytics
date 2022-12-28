# Performance Analysis of Players in T20 Men's Cricket World Cup 2022
```
Created a Power BI Dashboard which helps to review and compare performances of all the players in tournament. The dashboard also enables us to select best eleven of the tournament based on their performance based on some selection criteria
```
app link: https://shivanshka.github.io/Cricket_Analytics

## Video Demo
![demo](https://github.com/shivanshka/Cricket_Analytics/raw/master/Criket%20Analytics%20Demo.mp4)

## Steps:
- ### Data Collection:
    ```
    Scrapped all the data regarding match and world cup from www.espncricinfo.com and all details about players career from cricbuzz.com using Beautifull Soup library of Python.
    ```
- ### Data Transformation
    ```
    Performed initial data cleaning after scrapping such as player name correction, match id linking etc. using Pandas.
    Then, transformed the final data for dashboard using Power Query of Power BI.
    ```
- ### Data Modelling
    ```
    Connected all the datasets with based on some defined primary keys sucha s team and match ids. Also, created many measures, calculated columns and parameters for data analysis and dashboarding using DAX.
    ```
- ### Dashboarding
    ```
    Craeted final dashboard using Power BI visuals.
    ```

## Tools used:
    - Python -> Beautiful Soup, Pandas
    - Power BI -> Power Query, DAX