# Sasha Halpern's Data Science Portfolio
This repository exists as a home for my personal data science and analytics projects, completed for the purposes of self-learning and skill development. The data used as inputs for the projects below is not included in this repository, but is thoroughly cited below. 

## Projects
- Coral Bleaching
  
  As a fervent environmentalist and hobbyist scuba diver, I became interested in the impacts of climate change that are felt beneath the sea in addition to those we experience on land. I've seen with my own eyes coral reefs transform from vibrant, active ecosystems to a literal skeleton of what they once were. Coral not only provide a home for thousands of undersea animals and countless microorganisms, but they shelter us on land from the impacts of marine natural disasters by dispersing floods of water.
  
  For this project, I developed a dashboard with Tableau Public, which you can find on my Github Pages (https://sasharosehalpern.github.io/srh_portfolio/) or on my Tableau Public profile (https://public.tableau.com/app/profile/sasha.halpern). For this dashboard, my goal was to provide viewers with an understanding of the issue at hand and its breadth.
  
  Next, I developed a model in Python, primarily using pandas and scikit-learn to predict the severity of coral bleaching at a given location based on various features including water temperatures, distance from shore, reef depth, and more. Ultimately, using a random forest model, I was able to predict the categorical severity with an accuracy score of 89% on test data. Throughout this notebook, you will find notes on my thought process as well as plans to improve the model in the future given more time.


  Citations:
  
    - van Woesik, R., Burkepile, D. (2022) Bleaching and environmental data for global coral reef sites from 1980-2020. Biological and Chemical Oceanography Data Management Office (BCO-DMO). (Version 2) Version Date 2022-10-14
  
    - NOAA (National Oceanic and Atmospheric Administration). 2021. Extended reconstructed sea surface temperature (ERSST.v5). National Centers for Environmental Information. 
