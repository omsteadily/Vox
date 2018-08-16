# Query Project
This assignment was to use a public dataset on Google BigQuery to make recommendations to Ford GoBike in San Francisco for potential promotions in their nascent Bikesharing program.  Over the course of a month or so, I generated progressively more and more complex SQL queries, using the data to shape a set of proposals.

The idea I wanted to test was the use of bikes themselves as a marketing platform, and I wanted to measure their ability to target specific subsets of users.  Bikeshares are used mostly by commuters, but there is a healthy recreational contingent as well, and these audiences are quite different.  The unique challenge with bikeshare bikes is that there is very little control over where they go over time, unless you are constantly shuttling them around.  Given the assumption that workers could arrange bikes in respective commuter/recreational docks in the morning, I wanted to see whether the bikes would largely stay in their respective "territories" or wander off over the course of the day.  And I wanted to do it entirely in SQL.

You can [see the results in the iPython notebook](SF Bikeshare Analysis.ipynb).

(The use of CSVs to store query results, rather than pulling the whole dataset into Pandas or using the iPython/BigQuery library, was determined by the assignment guidelines.  I recognize that it isn't the most efficient way of doing this.)
