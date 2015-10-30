# SSRS-Usage-Stats
Set of usage reports for MS Reporting Services (SSRS)

* Usage Log - All Reports > Inventory of all reports on the server along with last viewed and view count information
* Usage Log - All Users > All users who visited the server along with the last visit date and total count of reports viewed
* Usage Log - by User Name > All reports viewed by selected user
* Usage Log - Daily Summary > Summary and details over the reports viewed on a selected date
* Usage Log - Dashboard > Top 20 most viewed reports, top 10 users, total view count by month

To install:
1. Open the project in Visual Studio 2013 or later
2. Edit ReportServer.rds replacing 'Data Source=kimball' with the name of your SSRS server instance. You might also want to switch from Windows Authentication to SQL Authentication.
3. Modify TargetServerURL in the Project Properties with the path to your SSRS server - e.g. http://localhost/reportserver. 
4. Finally, deploy the project to your server.


