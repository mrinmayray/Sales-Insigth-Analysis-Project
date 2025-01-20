
# Sales Insights Data Analysis Project

## Problem Statement

The Sales Director of a computer hardware and peripherals company faced challenges in reconciling sales data reported by regional managers with actual performance. Despite overall declining sales, regional managers consistently reported positive results, creating a need for accurate tracking and actionable insights to drive business strategy.
## Objectives

Reconcile discrepancies between regional sales reports and actual performance metrics.
Analyze regional sales performance to identify underperforming areas.
Examine historical trends to detect patterns contributing to the decline in overall sales.
Evaluate product performance across regions to uncover opportunities for improvement.
Propose a reliable sales tracking and reporting framework.
## Key Deliverables

A detailed report identifying discrepancies in regional sales data.
Visualized insights (dashboards and charts) showcasing regional and product performance.
Recommendations for operational and strategic improvements to address the sales decline.
A proposed framework for consistent and accurate sales reporting.

## Tools and Techniques Used

- Data Analysis: SQL, Excel, Python
- Data Visualization: Power BI
- Statistical Analysis: Trend analysis, correlation analysis
- Data Cleaning: Handling missing data, ensuring consistency across reports
- Presentation: Dashboard development and actionable reports

### Steps followed 

- Step 1 : Import data into Power BI Desktop, from my local SQL server.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Step 4: Identify and address any null values or errors in the data during the cleaning process..
- Step 5 : In the currency section of the sales transactions, it was observed that the values INR and USD were duplicated, appearing twice for unknown reasons. This issue was identified and corrected.
-  
![Image](https://github.com/user-attachments/assets/eea5be02-16c8-4b72-bde9-6e28c09d22f2)

- Step 6 : Following these steps, the dashboard creation process was initiated in the Report View of Power BI.
- Step 7 : Given the diversity of data encompassing various products, markets, and customers, a new visualization was created to effectively represent these dimensions. Using the Stacked Bar Chart from the Visualizations Pane in the Report View, the chart was designed to display a comparative analysis of these key attributes. This approach provided a clear and intuitive breakdown, facilitating better insights into the relationships and performance across products, markets, and customer segments.
- Step 8 : Visual filters, also known as Slicers, were added for the fields Year and Month. These filters enable upper management to easily view and analyze data on both a monthly and year-to-year basis, providing greater flexibility in exploring trends and making data-driven decisions.
- Step 9 : Two Card Visuals were added to the canvas—one displaying the Total Revenue and the other showing the Total Sales Quantity of products. These visuals provide at-a-glance metrics for key performance indicators, making it easier for stakeholders to assess overall business performance.
- Step 10 : An Area Chart was added to the report design area to represent revenue trends over time, segmented by Months and Years. This chart provides a clear visual representation of the company’s financial performance, making it easy to identify whether the organization is generating a profit or incurring losses compared to previous years.
![Image](https://github.com/user-attachments/assets/62369e7d-2929-4181-b570-a0d69993ee6c) 
 - Step 11 : The report was then published to Power BI Service.
 
 
![Publish_Message](https://user-images.githubusercontent.com/102996550/174094520-3a845196-97e6-4d44-8760-34a64abc3e77.jpg)

# Snapshot of Dashboard (Power BI Service)

![Image](https://github.com/user-attachments/assets/25ef6275-a831-4042-9496-5ba41bb35ff6)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Image](https://github.com/user-attachments/assets/cd71c810-89c6-46a8-8066-e85866f67521)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number Revenue & Sales

   Total Revenue = 987 Million

   Sale Quantity = 2 Million
   
           
### [2] Best Performing Market & Top Customer

  Best Performing Market = Delhi NCR

  Top Customer = Electicalsara Store

  ### [3] Top Product 

  The top product listed is blank, indicating that the product name was missing in the data we received. Given that more than 50% of the data is incomplete, we cannot accurately analyze or process it. We will inform the data management team or the IT team responsible for the data storage to ensure that future datasets do not contain blank product names. Additionally, if they are able to retrieve and update the missing product information in the database, the data can be corrected.

# Download Links

PDF Sales Analysis - [Download](https://github.com/user-attachments/files/18470161/Sales.Analysis.pdf)
