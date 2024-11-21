# Africa-Premium

## Table of content
- [Background](#Background)
- [Current Situation](#Current-Situation)
- [Task](#Task)
- [Step by step Analysis](#Step-by-step-Analysis)
- [Calculations and Insights](#Calculations-and-Insights)
- [Other KPIs](#Other-KPIs)
- [Dashboard](#Dashboard)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

## Background
You have been hired as a forecasting and budgeting analyst for “AfricaPremium,” a telecom company looking to enhance its financial planning and performance. The company has experienced steady growth over the past few years but now faces challenges with market saturation and increasing competition. Management expects you to refine the company's forecasting and budgeting processes to support strategic decision-making.

## Current Situation 
 Historical Performance: AfricaPremium has seen a 26% average annual revenue growth over the past three years, but the industry growth has been 35% over the past three years. 

Revenue Streams: The company generates revenue from Internet of Things plans, Fixed services, and value-added services. 

Market Conditions: Increasing competition from new entrants and changing customer preferences towards flexible and high-speed internet plans. 

Financial Data: Historical revenue and other KPIs(provided in the attached Excel workbook). AfricaPremium operates a January to December financial year cycle and is expected to grow at the same level as industry or even more for its next financial year.  

Strategy: AfricaPremium is aiming to reduce churn, increase new customers and remain dominant in the Telecom industry. 

## Task
Analyze the historical data to identify trends and patterns in revenue and corresponding KPIs. 

Develop a forecast model for the next 12 months (Jan-25 to Dec-25), considering factors such as market conditions, growth initiatives, and potential risks. 

Introduce any missing KPIs which is needed for the forecast model. 

Explain the assumptions and methodologies used in your forecasting model. 

## Step by step Analysis
### Note :

AfricaPremium has experienced a positive average annual revenue growth of 26%, indicating steady expansion and increasing revenues over time. However, the industry is growing at a faster rate of 35%, creating a 9% growth gap. This suggests that AfricaPremium may be losing relative competitiveness within the market. To identify the underlying factors contributing to this disparity, it is essential to analyze the historical revenue data for trends and patterns.

### - Analyze the historical data to identify trends and patterns in revenue.
 
To identify growth trends for each revenue stream, I used the historical revenue data and created line charts in Excel. These visualizations allowed me to observe revenue patterns over the past three years, highlighting fluctuations, seasonal variations, and overall growth trajectories for each stream. This step provided a clear overview of performance trends across all revenue streams.
  
  <img src="https://github.com/user-attachments/assets/275f8d90-0251-4575-ad46-a132784da2ef" width="850" height="500" >

- We can see positve fluctuations in the monthly revenues for all revenue streams. This pattern indicates that revenue is increasing overall but experiencing periodic ups and downs.
- Despite the inconsistencies in growth, the overall trajectory is upward, indicating growth.
- The spikes and dips in monthly revenue might be caused by factors such as customer demands, promotions, discounts etc.


### Calculations and Insights
### 1. Growth Rates 

By calculating the monthly growth rates, I gained insights into the reasons behind the fluctuating revenue trends we saw earlier for each revenue stream. These fluctuations reflect the dynamic nature of business performance. Understanding the underlying drivers of these variations enables the company to address risks effectively and leverage them as opportunities for achieving sustainable growth.

Formula:

*Growth Rate = (Current Revenue - Previous Revenue) / Previous Revenue*. 

or

*Growth Rate = (Current Revenue / Previous Revenue) - 1*

Format the cell to percentage.

 <img src="https://github.com/user-attachments/assets/bcbecef8-77a3-49f4-ac94-1a5d160e9197" width="600" height="450" > <img src="https://github.com/user-attachments/assets/a1701bdb-d4f7-4d94-b2d8-0b024104a478" width="700" height="500" > 
 						
- We can see that in some months, the growth rates reduced to negative causeing the revenues in those months to reduce drastically.
- The increase and decrease in growth rates might a results if customer behaviors or other factors. This is the reason the revenue has been fluctuating throughout the years.

  <img width="735" alt="Screenshot 2024-11-18 at 1 00 55 PM" src="https://github.com/user-attachments/assets/99e7aae8-e318-4f1b-b4c4-93792594caf4">

Formulas :

*AAGR = (=Average(all the yearly growth rates))*

*CAGR = (=((End year revenue/ Start year revenue)^(1/(Periods-1)) - 1)*

After calculating the monthly growth rates, I proceeded to determine the yearly growth rates and calculate both the **Average Annual Growth Rate (AAGR)** and the **Compound Annual Growth Rate (CAGR)**. The results, **26.26% (AAGR)** and **25.98% (CAGR)**, closely align with the **26% average annual revenue growth** provided in the historical performance data. This consistency confirms the accuracy of my calculations and indicates that I am on the right track.


### 2. Total Revenue Per Segment 

I calculated the total revenue generated by each revenue stream over the past three years (2022-2024) to determine their contributions to the overall revenue. This analysis helps identify which streams have been the most significant drivers of revenue growth and highlights areas with the greatest impact on the company’s financial performance.

<img src="https://github.com/user-attachments/assets/16510d79-27ed-427f-bfda-9c5816f655c6" width="700" height="500" >

- The analysis clearly shows that **Internet of Things (IoT)** generated the highest revenue compared to the other streams, while **Fixed Services** contributed the least over the years.
-  In fact, **IoT** generated approximately twice the revenue of **Fixed Services**, highlighting its dominant role in overall revenue performance and the relatively lower contribution from Fixed Services.

### 3. Forecast

Since the average monthly growth rate for each revenue stream was provided, I used it to forecast the revenue for 2025. The forecast was calculated by applying the formula:

*Forecasted Revenue = Previous Month Revenue × ( 1 + Monthly Growth Rate )*

This approach allowed me to project revenue for each month of 2025 by sequentially multiplying the revenue from the previous month by the average monthly growth rate.

<img src="https://github.com/user-attachments/assets/877a4429-fb87-4e63-b607-cbaa81ab779f" width="600" height="350" > <img src="https://github.com/user-attachments/assets/2e9e90bf-774c-41ed-afef-25bd63c316bb" width="700" height="500" > <img src="https://github.com/user-attachments/assets/8e44ccde-0f53-44d0-9f84-ef46dd6a08b3" width="700" height="500" >


- The forecast for 2025 shows a consistent increase in all revenue streams throughout the year, driven by the steady growth rate applied for each stream.
- Internet of Things (IoT) continues to generate the highest revenue, solidifying its position as the leading contributor.
- Fixed Services and Value-Added Services are projected to perform similarly, with only slight differences in their revenue contributions.


### 4. Yearly Total Revenue

I calculated the **yearly total revenue** for each revenue stream to verify whether **Internet of Things (IoT)** consistently generated the highest revenue across all years. This analysis helps identify if any other streams outperformed IoT in specific years, providing a clearer picture of revenue dominance and variability over time.

<img src="https://github.com/user-attachments/assets/8749c84d-682b-4b4f-a8fc-c6f3992dd333" width="500" height="200" > <img src="https://github.com/user-attachments/assets/130aa8b7-d165-4b98-9cde-f22810c5613a" width="700" height="500" >

- The years 2022-2025 are represented as 1, 2, 3, and 4, respectively.					
- The revenue generated by all streams shows a continuous increase over the years, including the forecasted period for 2025. 
- From the chart, it is evident that IoT consistently generates the highest revenue, while Fixed Services remains the lowest revenue contributor across all years.

<img width="664" alt="Yearly Growth Rate Table" src="https://github.com/user-attachments/assets/0fd0e723-35db-4e23-ab93-d95056bd1624">

The growth rate showed significant fluctuations over the three-year period. In 2023, it peaked at **34.62%**, reflecting strong performance. However, it dropped substantially by **16.73%** to **17.89%** in 2024, indicating a slowdown in growth. The rate rebounded in the following year, rising to **22.43%**, demonstrating a partial recovery but still below the 2023 high. This trend highlights potential volatility in the business environment or operational challenges affecting sustained growth.

### 5. Projections/ Assumptions
Economic conditions, inflation, interest rates, and consumer spending behavior can change unexpectedly, affecting demand and revenue. With this scenarioes we can effectively model how different assumptions will impact future revenue, providing a range of potential outcomes for strategic planning and decision-making.

Formulas:

Scenario 1 : *Next Year Revenue = Previous Year Revenue × (1 +  0.20)*

Scenario 2 : *Next Year Revenue = Previous Year Revenue × (1 + 0.35)*

 <img width="515" alt="Screenshot 2024-11-19 at 10 39 25 PM" src="https://github.com/user-attachments/assets/48ac78d6-f622-469b-beb4-664d3b4d4c9d">


 <img width="645" alt="Screenshot 2024-11-19 at 10 39 50 PM" src="https://github.com/user-attachments/assets/818b15e5-080a-4f8d-96b0-3114e96517c4">
					
- The base revenue is the total revenue generated in 2025 using the average monthly growth rate provided.
- In scenario 1, I used a lower growth rate to model the effect of competition or economic downturns. For instance, if the growth rate is reduced to **20%**, we are going to see a decrease in the overall revenue in 2025 as compared to the forecast revenue. 
- In scenario 2, I used a higher growth rate (e.g., industry benchmark **35%**), thus, if the market is favorable or growth initiatives succeed. We are going to see a massive improvement in the total revenue for 2025. 

### 6. Customer Base 

<img width="813" alt="Customer Base" src="https://github.com/user-attachments/assets/30922c13-a7c5-4c9c-b54a-d9ba01115cda">

- A large gap between active and closing bases may indicate inactive or disengaged customers, suggesting a need for re-engagement strategies.
- Hence, there is a need to enhance service quality, usability, and customer support to ensure active engagement.		

### Other KPIs 
### - Engagement Rate

I calculated the engagement rate using the active base and closing base. The active base represents the number of customers who engaged with the service within the period. Comparing this with the closing base provides the engagement rate.

Formula:

*Engagement Rate = Total Active Base / Total Closing Base × 100*

<img width="351" alt="Screenshot 2024-11-19 at 11 29 24 PM" src="https://github.com/user-attachments/assets/c9b1a52a-f7f9-457f-afaf-c4873f197fc0">

- This means that **57%** of the total customers are actively engaging with the service.
- With an approximately **73%** engagement rate, the Internet of Things has the highest engagement. While fixed values have the least engagement with an engagement rate of **11%**.
- This also explains why the internet of things generates the highest revenue while fixed values generate the least revenue throughout the years.

### Dashboard
This is a summary dashboard I created using Excel, highlighting some of the key insights of "AfricaPremium" revenue data.

<img width="1394" alt="Dashboard" src="https://github.com/user-attachments/assets/7950493c-43a7-4167-87e3-12d9887bb999">

### Conclusions and Recommendations
- The IoT stream shows high growth potential (e.g., a higher monthly growth rate, highest revenue generator, and high engagement rate), it could indicate strong market demand. Hence, investing further here may yield high revenue.
- Focus on IoT and Value-Added Services for their growth potential and higher ARPU, while implementing strategies to boost retention and engagement for fixed services.											
- Fixed Services shows slower growth or declining engagement, it may be less viable long-term unless the company can increase retention for this aspect.													
- Enhance Customer Retention Programs.  Introduce loyalty programs targeting fixed service revenue stream.
- Offer flexible or customizable plans to retain customers who might be considering switching to more dynamic competitors.			
- Regularly seek customer feedback through surveys and act on it to show that customer opinions are valued. This not only improves the product but also strengthens trust.
- Track the performance of each revenue stream quarterly and adjust strategies based on KPIs like ARPU, churn, growth rate, and engagement rate.										
