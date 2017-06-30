# mulesoft-weather-application
An application designed to know the weather and forecast of anywhere in the world, anytime.

### SCRIPTS ### (RUN BEFORE INSTALLING)

	There is a script needed to populate cities and countries on the database.

	PATH: ../src/main/resources/script/script.sql

	1. Make sure you have mysql installed on your computer.
	2. Connect through command line to mysql.
	3. Run source <PATH_TO_SCRIPT/script.sql> (it may take a while)

	Alternative: 
	Use Mysql Workbench to import the script.
	1. Connect to localhost:3306 with your user/pass
	2. Server tab/data import.
	3. Select sql file and import.

### INSTALLATION ###

	After running the script 

	1. Download the zip from github and extract.
	2. From Anypoint Studio select file->import and in the general tab select existing projects into workspace.
	3. Import from the root folder of the project.
	4. Right-click on the project->run as->Mule application.

### FEATURES ###

	- Wide city-country selection.
	- Current weather in those places.
	- Forecast for the next five days.
	- Tweet each 30 minutes about the current weather in Buenos Aires.

### TO DO ###

	- Email suscription for forecast.
	- Improve UI (maybe including AngularJS).
	- Finishing all remaining tests of the application.	
	- Send current weather by email.
	- Make an histogram of the weather based on user searchs.


