This project visualizes page view data from the freeCodeCamp forum. The dataset covers daily page views from May 2016 to December 2019. The visualizations include:

A line plot to show trends over time

A bar chart to show monthly averages by year

Box plots to show yearly and monthly distributions (trend & seasonality)

📁 Dataset
File used: fcc-forum-pageviews.csv

Data source: freeCodeCamp GitHub

Format:

c
Copy
Edit
date,value
2016-05-09,120
2016-05-10,135
...
✅ Visualizations
Type	Output File	Purpose
Line Plot	line_plot.png	Visualize page views over time
Bar Plot	bar_plot.png	Monthly average views grouped by year
Box Plots	box_plot.png	Trend over years and seasonality by month

📦 Technologies Used
Python 3

Pandas

Matplotlib

Seaborn

▶️ How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/time-series-visualizer.git
cd time-series-visualizer
Install required libraries:

bash
Copy
Edit
pip install pandas matplotlib seaborn
Make sure fcc-forum-pageviews.csv is in the project folder.

Run the project:

bash
Copy
Edit
python main.py
📂 File Structure
perl
Copy
Edit
time-series-visualizer/
├── time_series_visualizer.py   # Main analysis and plotting script
├── main.py                     # Calls functions to generate plots
├── fcc-forum-pageviews.csv     # Dataset file
├── line_plot.png               # Output: time series line plot
├── bar_plot.png                # Output: bar chart
└── box_plot.png                # Output: box plots
🧠 Learning Objectives
Time series analysis and visualization

Data cleaning using percentiles

Grouping and reshaping data with Pandas

Plotting with Matplotlib and Seaborn

Clear data storytelling through visuals

