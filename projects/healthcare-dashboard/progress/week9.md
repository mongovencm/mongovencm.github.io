[Home](../../../index.md) | [About Me](../../../about.md) | [Back](../dashboard.md)

# Week 9

- What did you do last week?

This past week, I finished cleaning up the training load data and combined its multiple CSV files into one dataframe to make it easier for analysis and visualization. I added a generic training load graph into the Streamlit dashboard as an initial piece, and I also created one comparison visualization that shows training load trends alongside injury reports. 

- What do you plan to do this week?
  
This week, I plan to focus on adding and creating more meaningful comparisons between datasets, as well as play more around with the interactive features and filtering capabilites that Streamlit has to offer. As I build out new visualizations and metrics, I will also pay attention to the dashboard layout and improve it by organizing sections and refining visualizations so that trends and potential risk factors are easier to interpret.

- Are there any impediments in your way?

While I have cleaned and structured all the data, I will still need watch for cases where datasets use different athlete identifiers, column names, formats, or structures that may require additional preprocessing before they can be compared. 

- Reflection on the process you used last week, how can you make the process work better?

I think my process of separating data cleaning from dashboard development has worked well so far. Creating the cleaning scripts made it easier to utilize the datasets in Streamlit. As I get deeper into my comparisons I plan to keep the same approach. If there are any cases where the data needs further alteration to be able to compare, I will modify the cleaning files instead of performing transformations within my Streamlit script.
