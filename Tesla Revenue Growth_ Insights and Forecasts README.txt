An image of blue sticky notes on a wall with a yellow one standing out 

Tesla Revenue Growth: Insights and Forecasts
This project provides a comprehensive analysis of Tesla's revenue growth using data scraped from Macrotrends. The analysis includes key insights such as Year-over-Year (YoY) growth rates, revenue forecasting, and milestone annotations. With advanced data visualization and forecasting techniques, the project highlights Tesla's exponential growth trajectory.
1) Project Overview
Tesla has consistently been a leader in innovation and growth within the automotive and technology industries. This project analyzes historical revenue data, forecasts future revenue, and identifies trends and milestones in Tesla's journey. Using Python, data is scraped, processed, and visualized to provide actionable insights.
2) Features
* Web Scraping: Revenue data extracted from Macrotrends using BeautifulSoup.
* YoY Growth Analysis: Calculation of Year-over-Year growth percentages.
* Revenue Forecasting: Future revenue is predicted using Exponential Smoothing and log-transformed revenue data.
* Growth Categorization: Categorized YoY growth into "High," "Moderate," and "Low Growth."
* Milestone Visualization: Tesla milestones (e.g., Model S and Model 3 launches) are annotated on the revenue timeline.
* Interactive Charts and Insights: Detailed plots for growth trends and forecasting.
3) Instructions to Run the Code
Dependencies
To run the project, you need the following Python packages:
* pandas
* numpy
* matplotlib
* statsmodels
* BeautifulSoup (from bs4)
* requests
Steps to Execute
1. Clone the repository:  
2. Install the dependencies: pip install -r requirements.txt
3. Run the Jupyter Notebook or Python script:
   * Open the tesla_revenue_analysis.ipynb file in Jupyter Notebook.
   * Or execute the script: python tesla_revenue_analysis.py
   4. Visualizations and CSV outputs will be saved in the outputs/ folder:
   1. Forecasted revenue: tesla_revenue_forecast_corrected.csv.
   2. Growth analysis: tesla_revenue_analysis.csv.
4) Results
1. Historical and Forecasted Revenue
   * Historical data shows a consistent growth trend.
   * Forecasted revenue predicts exponential growth in Tesla's future revenue.
Visualization:
  

2. Years with Significant Growth (>50%)
   * Tesla experienced several years with high YoY growth (e.g., 2011, 2013, 2018, 2021).
Significant Growth Years Table:
Years with >50% Growth:
             Revenue  YoY Growth (%)      Forecast  Log Revenue  Log Forecast
Date                                                                        
2011-01-01    204.0       74.358974   1150.219036     5.323010      4.998000
2012-01-01    413.0      102.450980    458.813559     6.025866      5.671991
2013-01-01   2013.0      387.409201    626.594309     7.607878      6.526256
2014-01-01   3198.0       58.867362   3330.566403     8.070594      8.598691
2016-01-01   7000.0       73.010381   4968.837577     8.853808      9.054914
2017-01-01  11759.0       67.985714   9538.699890     9.372459      9.596062
2018-01-01  21461.0       82.507016  16076.211082     9.974039     10.095959
2021-01-01  53823.0       70.671613  37918.023034    10.893475     10.868547
2022-01-01  81462.0       51.351653  72885.995705    11.307904     11.436296
3. Milestones
Tesla milestones are highlighted alongside the revenue timeline:
   * 2012: Model S launch.
   * 2017: Model 3 launch.
Visualization:
  

4. Categorization of Revenue Growth
   * Growth is categorized into:
   * High Growth (>50% YoY): 9 years.
   * Moderate Growth (20-50% YoY): 2 years.
   * Low Growth (<20% YoY): 4 years.
Growth Distribution Chart:
  

Insights
   * Tesla's revenue experienced exponential growth, with major contributions from milestones like Model S and Model 3 launches.
   * The company has consistently seen high growth years, indicating effective scaling and market expansion.
Note: Data Source ->  Revenue data is scraped from Macrotrends.