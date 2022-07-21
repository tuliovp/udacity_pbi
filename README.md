# udacity_pbi
Power BI - Udacity Nanodegree Final Project

<h1>Description</h1>
                  <hr>
                  <p>
                    This is a 3-month course to master in-demand skills necessary to become a data analyst like data pre-processing, visualization and analysis using Microsoft Power BI as the primary tool.
                    <br><br>
                    The following sections had projects for each one and were mandatory as part of the syllabus:
                    <ol>
                      <li>Introduction to Preparing and Modeling Data</li>
                      <li>Creating Visualizations with Power BI</li>
                      <li>Advanced Data Analysis</li>
                    </ol>
                    Some topics studied include:
                    <ul>
                      <li>Power BI’s built-in Extract-Transform-Load (ETL) tool</li>
                      <li>Power Query and M</li>
                      <li>Foundational data modeling principles</li>
                      <li>DAX (Data Analytics Expressions)</li>
                      <li>Advanced data visuals</li>
                      <li>Filters and Slicers</li>
                      <li>Drill-through and Bookmarks</li>
                      <li>Accessibility and user-friendly design</li>
                      <li>Statistics and Forecasting (Linear Regression)</li>
                      <li>Custom formulas</li>
                      <li>Troubleshooting and optimization</li>
                    </ul>
                    <img src="/media/udacity_pbi.jpg">  
                    <br><br>
                    <b>Customer Insights:</b><br><br>
                    <img src="/media/pbi_customer_insights.jpg">
                    <br><br>
                    <b>Product Insights:</b><br><br>
                    <img src="/media/pbi_product_insights.jpg"> 
                    <br><br>
                    <b>Demographics:</b><br><br>
                    <img src="/media/pbi_demographics.jpg"> 
                    <br><br>
                    <b>Linear Regression:</b><br><br>
                    <img src="/media/pbi_correlations.jpg"> 
                    <br><br>
                    <b>Analysis:</b><br><br>
                    The following is a fairly simple analysis - as the goal of the course was mainly to learn technical features - from data related to our 1,000 customers, 17 products in our inventory and general demographic sources about the clients’ locations. <br><br>We may first notice the distribution of the average income by state is concentrated on the east side (District of Columbia having the highest), although California is where the company has more customers.
                    <br><br>
                    <img src="/media/pbi_maps.jpg"> 
                    <br><br>
                    There is a visible correlation between Sales and Customer’s Income, with a R² of 0.78, as well as between the products’ Customer Rating and Return Rate, with a R² of 0.69. The linear regression models for both are as follows:
                    <br><br>
                    <img src="/media/pbi_correlations_report.jpg"> 
                    <br><br>
                    However, despite the positive correlation between Income and Purchases (Sales), we are able to see that the customers with a predicted income between $70,000 and $89,000 are currently the biggest group, spending more – in total - than customers who earn from $90,000 to $109,000. The ones with a predicted income of $110,000 or more comes as the third biggest group, and higher sum of purchases – being the one we should focus during the marketing campaign. See below:
                    <br><br>
                    <img src="/media/pbi_customer_pred_income.jpg"> 
                    <br><br>
                    Looking by individual purchases, instead of the total, can confirm that the ones spending more (> $110.00 per purchase) are the ones with the highest average predicted income. The bigger group being individual purchases with values higher than $130.00. Furthermore, ages between 40 and 43 should be priorised.
                    <br><br>
                    <img src="/media/pbi_6monthpur_predincome.jpg"> 
                    <br><br>
                    The customer with the highest predicted income is Jon Little (ID JLit30836) and the Spring T-Shirt is the product that will be advertised the most. The algorithm that decides which product to recommend is a mix of the average temperature of the customer’s state and their predicted income, as seen below:
                    <br><br>
                    <img src="/media/pbi_product_fit.jpg"> 
                    <br><br>
                  </p>
                  <br>
                  <h1>Read more</h1>
                  <hr>
                  <p>
                  Feel free to download the repository and check how everything's working for yourself in the <a href="https://app.powerbi.com/view?r=eyJrIjoiYTU2YjAwMDktMWU2My00MDYzLWI3NDItYTYzZGM3MzFhYzEwIiwidCI6ImZiY2RmY2NmLTQ4MjItNGM2Yy04ZDRkLTk3OTM1MDhkM2I4NCJ9">Report</a>. And please let me know if you have any comments.
                  </p>