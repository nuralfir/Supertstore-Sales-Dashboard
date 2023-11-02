<h2>Sales Performance Dashboard in Superstore</h2>
<h3>Business Problems</h3>
This project explores the analysis of sales performance in 2017 as a reference and evaluation for store managers in each region. This project was created because the process of analyzing and evaluating sales performance is still done manually, so it takes a long time in the process. Also, in terms of the effectiveness of data processing from end-to-end if each period of sales performance evaluation is still using conventional methods. Therefore, this project was launched to produce an interactive dashboard related to the results of sales performance analysis and is expected to facilitate and improve the evaluation process for store managers in each region, so that it can help in making decisions and optimizing strategies for increasing sales in this Superstore, especially sales in each region.<br>
Besides, the store managers also want to know how the sales of the products are in each region, so they refer to several metrics, namely:
<ul>
  <li>Total Sales, Transactions, and Customers by Year</li>
  <li>Sales Growth</li>
  <li>Branch Sales Performance</li>
  <li>Sales Profit</li>
</ul>

<h3>Dataset Description</h3>
The data used is a public dataset entitled Superstore, where the dataset contains information related to transactions from the sale of products that have been sold from 2014 to 2017 in several cities in the US. The dataset consists of three tables, namely the Customer table which contains the names of customers registered as buyers at Superstore; the Categories table which contains a list of products sold by Superstore; and the Order table which is a table of transactions resulting from the sale of goods along with a list of customers who make purchases. This dataset is formatted in xlsx, so that the dataset can be directly connected with Looker Studio.

<h3>Build a Dashboard</h3>
The dashboard was built using Google's Looker Studio. The dataset files are uploaded into Google Drive so that they can be accessed by Google Sheets, and then can be connected directly into Looker Studio as the main data source in this project.
<br>![image](https://github.com/nuralfir/Supertstore-Sales-Dashboard/assets/109499310/bc1c0f9f-0b16-4466-a949-b1067f5d53f3)

<ol>
  <li>Total Sales, Transactions, and Customer by Year</li>
  This metric uses a scorecard feature that explains numbers in a short and easily visible way, making it very suitable for this metric which functions to see the 'big numbers' of the     current conditions that are happening. The scorecard is attached to each variable/dimensions such as Sales, Transaction, Customer and also Profit.
  <br>![image](https://github.com/nuralfir/Supertstore-Sales-Dashboard/assets/109499310/8abf6bb3-9474-4095-8b8b-ab43d687a33f)
  <li>Sales Growth</li>
  This metric uses a line chart because it is suitable for seeing the growth/change of information based on a time line. The growth of sales from 2014 to 2017 is easily seen by this       chart, so we know the highest or lowest point of sales in this 4-year timespan.
  <br>![image](https://github.com/nuralfir/Supertstore-Sales-Dashboard/assets/109499310/19276811-7707-46e1-a483-aedf48b9100f)
  <li>Branch Sales Performance</li>
  In this metric, the graphs used consist of pie charts, tables, scorecards and vertical bar charts. Pie charts serve to determine the composition of sales of products when viewed from    each region and tables that contain what items are most purchased by customers. Then the scorecard which functions to display the average duration of delivery for each type of           shipping that has been carried out by this Superstore. For the vertical bar chart, this graph serves to find out how many sales have been made when viewed based on the use of the type   of shipping chosen by the customer.
  <br>![image](https://github.com/nuralfir/Supertstore-Sales-Dashboard/assets/109499310/2baf9473-2561-41f9-a4c7-ddb871b2a10f)
  <li>Profit Sales</li>
  The graphs used in this metric are treemap and vertical bar chart. Treemap is used to see the composition based on the color that has been determined by region. The darker the color,    the region has the highest profit. Vertical bar chart serves to find out how much profit is generated based on the type of customer segment.
  <br>![image](https://github.com/nuralfir/Supertstore-Sales-Dashboard/assets/109499310/a0d6bae2-94de-4eaa-9128-58ff8f4e4797)
  <li>Dashboard Features</li>
  This feature in the dashboard uses data filters based on date and region. We can sort out what data we want to display based on the day, month, or year, as well as which region. Also,   each graph can display tooltips that make it easier for users to see information briefly just by pointing their mouse.
  <br>![image](https://github.com/nuralfir/Supertstore-Sales-Dashboard/assets/109499310/c382fbc1-c733-4736-9dd0-25315f5aaec4)
  <br>![image](https://github.com/nuralfir/Supertstore-Sales-Dashboard/assets/109499310/cdb97cd4-3773-439c-b824-0c020aa77953)
</ol>

<h3>Findings & Insights</h3>
Some insights found overall (2014-2017) are as follows:
<ul>
  <li>In each year, sales tend to increase in the months leading up to the end of the year and decrease in the months of the next year. This factor is thought to occur because the months at the end of the year have many specific events such as Halloween, Thanksgiving, Christmas and New Year for US citizens.</li>
  <li>The Western region is the region that contributes the most sales compared to other regions. This is in line with the higher profits generated compared to other regions.</li>
  <li>Regular customers dominate sales so that the profit generated is also higher than corporate and home office customers.</li>
  <li>Standard class is the favorite type of shipping to use, although the average delivery of goods to arrive takes 5 days.</li>
</ul>
