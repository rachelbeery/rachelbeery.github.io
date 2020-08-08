---
layout: post
title:      "What data visualization library is the best?"
date:       2020-07-31 15:08:24 -0400
permalink:  mod_1_project
---

No matter how good your findings are they won't have their intended impact without being able to convey your knolwedge to others. As data scientists we will need to harness the power of communicating our data and findings. Data visualization is one of the most important tools to communicate data science and educate to non-technical audiences. In this project I experimented and utilized 3 different data visulization libraries that I will give a breif overview of.

# 1. Matplotlib
The foundation to data visualization libraries using Python is undoubtebly Matplotlib. It has incredible power and complexity which is why there are many other libraries that are built on top of the preexisting features of this visualization library. This library can be used as a base for first understanding the data and exploring phenomenon in the data. The styling and very basic and simple which can be useful as a beginner data science. The following libraries utilize the tools of this foundation to build visualizations with less code and more customization options.

![](https://raw.githubusercontent.com/rachelbeery/Mod-1-Project/master/visuals/runtime_minutes_plt.png)

# 2. Seaborn
One of the most popular libraries for building a well put together and aesthetically pleasing visualizations is Seaborn. Less lines of code are necessary to create basic or complex visualizations that can be used for any presentation. Additionally, Seaborn has the power to make more advanced plots including categorical plots. An example below shows a horizontal bar chart where the gross movie profits are compared by genre category. Additionally the bars of the graph show the portion of the domestic gross profits in dark blue with the overall worldwide gross profits. To also optimize both libraries one can create more advanced visualizations using Seaborn code and then customize using the code from matplotlib.

![](https://raw.githubusercontent.com/rachelbeery/Mod-1-Project/master/visuals/horiz_domestic_intl_sns.png)
# 3. Plotly
If interactivity and customization is what you are looking for than look no further than to Plotly! When thinking about and exploring what would be the best visualization to show details for certain data points on a specific graph I found that plotly was the best option for this.

Plotly express is additionally a build in on top of the already existing plotly library that as it's name implies makes code even more efficient and quick to make than plotly itself. 

The following display below shows plotly and how it can be used to answer the question of whether IMDb ratings affect the profitability of a given movie. With plotly express we were able to make the visualization interactive so that the audience is able to toggle over any point on the plot and see the specific move name and details. 

![](https://raw.githubusercontent.com/rachelbeery/Mod-1-Project/master/visuals/imdb_rating_gross_px.png)

