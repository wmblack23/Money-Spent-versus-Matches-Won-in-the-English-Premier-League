# Money-Spent-versus-Matches-Won-in-the-English-Premier-League

This notebook examines **the role that money plays in teams' success in the English Premier League dating back to the 2000-2001 season.**

- We load season data from 2000-'01 until 2019-'20 via Excel with Pandas.  Data was found on Reddit, The Guardian, and Planet Football (linked in file).

- We write a function with Plotly.express which allows us to produce a scatterplot with a line of regression (showing expected points based on total pounds £ spent) for any season since 2000.  I give two examples: 2019 and 2015*.  The graphs are interactive, and by simply hovering over any given point, you can see the name of that team, their final standings for that season, their total dollars spent, their total points won, and also their expected points won in regards to the line of regression.

- We also plot various bar graphs and examine DataFrames to show how the gulf between what the Top 4 teams and the Bottom 3 teams spend has only gotten larger and larger over the years.


**For whatever reason, the plotly.express graphs do not show up when I download my notebook as a .ipynb.  I include a screenshot of the graph for 2015 so you can see how they look, but please feel free to run the code yourself and try it out.  Aside from the interactive hover feature and line of regression, you can zoom in on various aspects of the graph, toggle spike lines, and more!**

---
**Michael Black**
