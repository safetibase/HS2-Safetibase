# SafetIbase
SafetIbase is an award winning system to improve the identification, management and communication of health and safety hazards for construction projects. Funded by i3P, it is an open source solution for the industry.

#####################################################

Deploy Safetibase on a SharePoint Site
-----------------------------------------------------
Requirements:
- Windows 10
- SharePoint Project Site (sites from other templates might not work)
- Owner rights on your SharePoint site
-----------------------------------------------------
To install SafetIbase on a SharePoint, follow the steps below:
- Download these files to your C drive (downloading the whole repo from Github using the green 'Code' button on the top right, the select 'Download ZIP')
- Unblock the zip file (right click > properties > check the 'Unblock' checkbox)
- Open PowerShell (PowerShell ISE is the easiest option)
- Open 'Manual Install.ps1'
- In the User input section, change the Url to the url of your SharePoint site
- Go to your SharePoint site > 'Site Contents' > 'Site Assets'
- Drag and drop the content of the 'Site Asset' folder from the install files
- Run the script
- To find your SafetIbase page, go to 'Site Contents' > 'Site Assets' > 'pages' > '3.0' > 'dashboard.aspx'
-----------------------------------------------------
