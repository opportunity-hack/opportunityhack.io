---
title: PopSteam
mini_description: Provides a way for teachers and parents to find interesting
  STEAM subjects for their children using popular culture
github_link: https://github.com/opportunity-hack/popsteam
youtube_link: https://www.youtube.com/embed/yrvmrREXHt0
features:
  - Gathers information from Reddit, IMDb, Wikipedia, Steam, YouTube, Twitter,
    Google Trends, Nasa.gov, Teachengineering.org, and AskDrUniverse.com
  - Includes links to relevant popular posts and data regarding the relative
    popularity of said posts or given query words which are then graphically
    displayed, as well as links to related learning resources
---
The purpose of this project is to help identify trends in popular culture to assist educators in finding ways to better introduce STEAM concepts to children. Via web scraping and API calls, this project gathers information from Reddit, IMDb, Wikipedia, Steam, YouTube, Twitter, Google Trends, Nasa.gov, Teachengineering.org, and AskDrUniverse.com. This information includes links to relevant popular posts and data regarding the relative popularity of said posts or given query words which are then graphically displayed, as well as links to related learning resources. The application is accessed via a Heroku deployment and includes the necessary web files, but can also be configured to run locally. Generated URL links are stored in a .csv file, and graphs are saved as a .png. Any query word may be used and information is gathered live, though runtime can be near 30 seconds. As such, we have also included a list of suggested topics, as gathered through mining documents pertaining to California's educational curriculum, whose results have already been generated and thus may be accessed more quickly, though are not gathered in realtime and so may become outdated.