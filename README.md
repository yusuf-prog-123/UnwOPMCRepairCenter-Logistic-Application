# UnwOPMCRepairCenter
This is a logistic application designed for a repair facility that will take used home networking devices (ADSL routers, ONT, ZTE) that are returned from customers and categorize them as configured or defective after checking the router, the categorization allows us to extract just repaired devices. A database is created with mysql and a <b>SQL connecter library</b> is used on the jave netbeans project to connect to the SQL database that has already been created. This is made for the repair shop inorder to provide high effeceincy when taking care of huge load of network devices that are being returned from customers.
There are multiple tabs which are responsible for different function

Tab1-Input RepairCenter-->You'll be Using a barcode reader, enter the Unique MAC address, pick the kind and location from where it has returned, and press enter to update the database. record will be enterd to the <b>input repair center</b> table of database

Tab2-Repair Stock-->Select configured or faulty with the name of the technitian will be updated into <b>repaired stock</b> table in the database

Tab3-Repaired Stock Taken-->Read Barcode when withdrawing and add to the <b>table withdrawn</b> in the database with the name of withdrawer 

Tab4-Home-->Gives the count of number of Different types of tool availabe 

Tab5-Montly Summary-->Export the summary for each month of year entry to a Excel Sheet


![Tab1](https://user-images.githubusercontent.com/117608882/221508700-5c58e39c-ac12-4304-bce3-772bf68184c0.png|width=250)
![Tab2](https://user-images.githubusercontent.com/117608882/221508783-b88e0f53-de22-442e-8787-3ce7954fac92.png)
![Tab3](https://user-images.githubusercontent.com/117608882/221508808-e99d4c62-e064-4e77-b78d-b9d45a088792.png)
![Tab4](https://user-images.githubusercontent.com/117608882/221508829-ca737771-dc3f-4727-9ea6-22c77a95d5db.png)
