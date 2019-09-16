# plotly-challenge
In this project I built an interactive dashboard to explore the Belly Button Biodiversity DataSet.



## Step 1 - Plotly.js
Used Plotly.js to build an interactive charts for the dashboard.

* Created a PIE chart that used data from samples route (/samples/<sample>) to display the top 10 samples.
  Used sample_values as the values for the PIE chart and used Used otu_ids as the labels for the pie chart and Used otu_labels as the     hovertext for the chart.

* Created a Bubble Chart that used data from samples route (/samples/<sample>) to display each sample. Used Used otu_ids for the x values and sample_values for the y values.
  
  Updated all of the plots any time that a new sample is selected.
  
  
 ## Step 2 - Heroku
 
 Deployed Flask app to Heroku here: 
 Used sqlite file for the database.





