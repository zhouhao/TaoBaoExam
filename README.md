TaoBaoExam creates questions first. When an exam is set up, the teacher has two ways to select questions from the database into exam, which means one question can belong to many exams, and one exam can have many questions.     


This project is written by ASP.NET 2.0, and uses Ajax.        
As ASP.NET 2.0 doesn't support Ajax default, you should download "[ASPAJAXExtSetup.msi](http://www.microsoft.com/en-us/download/details.aspx?id=883)" first, and install it.     

You can find more information about it here:http://asp.net/ajax/documentation/live/InstallingASPNETAJAX.aspx    

To run it well, you must config the SQL Server connection. I choose SQL Server 2005, and the database file is in the directory `App_Data`.     
Open `Web.config`, modify the following parameters.    

```xml
<connectionStrings>
  <add name="ConnectionString" connectionString="Data Source=XXXX;Initial Catalog=Examination;User ID=XXXX;Password=XXXX" providerName="System.Data.SqlClient" />
</connectionStrings>
```

