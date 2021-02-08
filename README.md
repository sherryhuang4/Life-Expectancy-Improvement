# Life-Expectancy-Improvement

## About

I took a Statistical Graphics and Data Visualization class for my J-term 2021 class. My first mini-project for the class was to replicate an existing graph, then give the graph a "glow-up" and a "glow-down" (re-design it as well and poorly as you can).

The graph I used comes from [Our World in Data](https://ourworldindata.org/life-expectancy), specifically the graph under "Differences in life expectancy across the world." It shows life expectancy of countries around the world from 1543 to 2019.

## Original/Replication

In my replication, I treated the original graph as a static map representing life expectancy in 2015, because this was the most recent year available in the data set at the time. More notes about the graph can be found at the end of the paper, but some countries' life expectancies are not shown because country names did not line up across data sets.

## Glow-Up

For the glow-up, the biggest issue I wanted to address was the idea that small countries were difficult to see. Because geographic size is not a priority in this visualization (that is, there's no reason countries *have* to be their respective sizes), I chose to re-design the original graph as a "binned" version. In this "glow-up," small countries are equally as visible as large countries, but the general shape and patterns of different continents are still visible.

## Glow-Down

I chose to make the original graph worse by re-designing it into a pie chart. Pie charts are notoriously bad for displaying data because humans are not good at measuring angles, which is exactly what pie charts do. For example, some pie "slices" can be difficult to tell which one is larger. Another detail that makes this re-design so inconvenient is that it's extremely difficult to find a specific country. Countries are only labeled by their 3-letter ISO code. And lastly, patterns in continents are very difficult to see. For example, European countries generally have a higher life expectancy, but that is not something that can be easily found in the pie chart.

## Details

The description of the project can be found [here](http://www.swarthmore.edu/NatSci/aluby1/stat041/Projects/proj-1.html).