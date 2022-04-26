# 13F-scraper

Scraper Overview: </br>
- Continually scrapes 13Fs from SEC Latest Filing website
- Extracts portfolio from the online 13F
- Converts HTML/XML portfolio into excel sheet and saves it locally
- All relevant data related to each form is saved in database

Analysis Overview:
- Merges the most recent 13F by each comapny into one dataframe -> Allows us to see which stocks are favorable amongst institutions
- View how a certain company has altered their portfolio over time -> Allows us to see what positions have they increased or decreased
- Given a specific ticker program can find all holders of that ticker -> Able to analyze institutional holdings for personal portfolio
