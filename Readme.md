
# Classic Model Power BI Project

## Implemented a power bi project to analyse the sales and net profit of different products. Filtering it based on time and product name to get deeper insight.


**<p align="center">Dashboard Preview</p>**

![Dashboard](./Dashboard%20Preview.png)
<br>

### Steps

1. clone the repository using git command or by downloading ZIP file <br>
`git clone repository-url`

 2. Open the Power BI file named *ClassicModel.pbix* which contain the dashboard detail analysis

> [!Note]
> If there is any issues in loading the data or visual then follow either of the two Method:\
Method 1:
Load the excel dataset named **Classic Model Dataset.xlsx** in Power BI and then try to open again the pbix file <br> <br>
Method 2: <br>
> - Install MysqlWorkbench and create a new connection named *classic* connection
> - Run the SQL script named **MySQL Script.txt** and it will automatically create all the necessary table with data
> - Open docx file named **Query+-+Create+View+for+Power+BI+.docx** which contain an sql query. Execute it in sql and a new view will be created with named **sales_data_for_power_bi**.
> - Finally, open that view in power bi with open data source option > database>MySQL

Thank you for your time and have a nice day :smile:



