#Quantico Cohort 06-- Individual Cloud Applications Development Project

## Rhay C. Scott

### July 12, 2020

IT Training Compliancy Tracker
------------------------------

Background
----------
Throughout my career as an IT, I have encountered many companies that lacked the ability to readily quantify the quality of IT personnel in respects to training.  Some have strict guidelines from onboarding to duty requirements, however, lack a policy or mechanism that allows managers to assertain the status of personnel and their training.
While attending MSSA, I would like to build an application that could be utilized as a tool that could help visualize I.T. training deficiencies and compliancy.  

Method
------
-Using the standard company structure, billets, and IT Certifications this application will be able to display personnel current training and certification compliancy status.  

-The tracker will be able to give certification details linked to a specific duty utilized by a specific department.  It will be able to describe the reason for the requirement; be it onboarding, yearly maintenance, hiring, or government IA compliancy.  The tracker will list the training sponsor organization and it's frequency.

Planning Requirements Example
-----------------------------

Thomas Thompson	- Triage_Srvc_Oprtr	- Hlp_Dsk	- Onbrd_date	- Comptia -	Sec+Ce	 Compliant	Expires 20200831

Kira Kirrason	- Triage_Srvc_Oprtr	- Hlp_Dsk	- Onbrd_date	- Comptia	- Sec+Ce	 Compliant	Expires 20200229

Todd Toddmanson	- Software_Dev -	DEVOPS	- Onbrd_date	- MSSA Cert	 - MSFT	 - NonCompliant	Expires 20201130


Extraction Example
------------------
Manager from Hlp_Dsk has access to Hlp_Dsk to view employee information.  He will be able to view employee status, update employee status, select common preconditioned queries and statistical information on screen, and export information to a readable spreadsheet.  A "preconditioned query" option example would be a list of employees who are not compliant.  In this example, Kira Kirranson would appear in the spreadsheet along with a chart that displays that 50% of the department is non-compliant.

Input Example
-------------
Two main input methods will be .csv and manual.  This information populates the database to fulfill the extraction requirements.  Manual on screen will require user to be prompted by a form with required entries.  .csv entries will require a local file be uploaded for extraction via several prompts.  All portions of the User interface will be developed within the confines of the MSSA curriculuum.

UI Output Example
-----------------
Once user selects preconditioned query, an on screen spreadsheet and pie chart will populate the screen with information.  An "export to file" button will generate a file that can be viewed in separate spreadsheet programs. 

Database Table Example
----------------------
--Employee
 -Fname
 -Lname
 -Middle
 -Address
 -HomePhone
 -WkPhone
 -Email

--Certifications
 -CISCO
 -COMPTIA
 -DAU
 -ISC2
 -GOV
 -MSSA
 
--Billets
  -PM
  -SCRUM_MSTR
  -SFTWR_DEV
  -HD_Tech
  
 --Departments
   -HQ CIO
   -INFOSEC
   -IM/KM
   -HLP_Dsk
   -NETOPS
   -DEVOPS



--Dependency Tables
--Certification Details
--Billet Details
--ManagerAccess

Design Planning Features
------------------------
Planning will imphasize scaling the project based lateraly on what is taught in MSSA.  The frontend of the user's GUI will be based on a style of entry boxes programmed in c#, while the backend will contain database repositories for information callback.  Statistical information will  be generated that show retention requirements, deadlines, certificate expirations, and compliancy/ non-compliancy rates by department.

Standard software development life cycle, however, understand that puts development in constant sprint phases.  I will identify all of the requirements that need to be in my application to showcase the extensiveness of its development.  I will define what each of the attributes require and ensure that a time block is designated for product feasibility for feature lockdown.  The next phase of design will ensure that the methods used to generate the application is conducive with skills learned in MSSA and within the scope of prioritization and completedness.  This phase will also solidify what each element should appear as to the users.  Between coding, testing, and deployment are time blocks set from the design phase to esure a complete product is ready for official release and deployment.