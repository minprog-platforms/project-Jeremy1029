# **Fantasy Football Selector**

## *Explanation of the project*
### The problem I want to fix is the problem of picking the perfect fantasy football team.
### This project will scrape football player's data from the site: "https://www.transfermarkt.nl/" or "https://fbref.com/en/". 
### I will try to implement various criterea which the user can stipulate, in order to pick the best players for them based on the data.
### This program is meant for people interested in the sport from the age of around 16.
### There are other sites who do fantasy football, but this is usually limited to one league only.
### Depending on how elaborate I can make the site, people in real football may have real world uses for it as well.

## Prerequisites
### I will need to find out if I'm able to scrub the sites in question for the data necessary to make the site work.
### I think I will need SQLalchemy in order to get the access to the databases for the information on the football players.
### Furthermore, the .executemany function would seem to be useful for what I want to accomplish, because it can handle larger amounts of data as well as data stored within other files.
### I would also need to use the connect to mySQL server function, as the site would need to let many different users connect and build their own teams.
### Here are a couple of sites that attempt to accomplish something similar: https://draft.premierleague.com/,https://www.fantasyfootballfix.com, https://www.laligafantasyone.com/.
### These sites essentially implement what I have already explained in the explanation of the project. However, these sites only cover one league. 
### Looking at these sites it should be possible to implement it in a very similar manner. 
### The hardest part (assuming I am relatively easily able to scrub the databases) in my opinion will be implementing the various queries. These queries are necessary to pick the best players according to the users' criteria.

###### Jeremy Adei
