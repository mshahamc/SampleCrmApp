# Running Sample CRM App locally:
* Open a terminal window and navigate inside the folder that contains the Sample CRM App and enter these commands.
* cd SampleCRMApp/
* npm start

* The SampleCRMApp will run on localhost:3000

# Creating the Applications in Studio

* Open the creators studio (https://studio.contactcanvas.com) and navigate to the Edit Apps Section
* Create a new app with the name “SampleCRMApp”
* Navigate to the configurations of the app you just created and enter the url configuration as (localhost:3000)


# Integrating with SalesForce

* Install the DaVinci App for SalesForce (https://login.salesforce.com/packaging/installPackage.apexp?p0=04t0g000000RaCh)
* Edit Softphone Layout: 
	* Type softphone layouts in the Setup Quick Find
	* Click the Menu Link that appears for softphone layouts
	* Click Continue button to pass by the help screen
	* In the work area, click the New button
	* Enter a Name for your new layout
	* Click the Is Default Layout check box
	* Save

3. Edit Call Centers
    * Once the App is installed, users must be added to the Salesforce Call Center:
	* Log into Salesforce with administrative privileges
	* Navigate to Setup
	* Type call centers in the quick find
	* Click the Call Centers menu link that appears
	* Click Continue button to pass by the help screen (To learn more about Salesforce Call Centers, select the links provided)
	* Click AMC Salesforce CallCenter (Do Not click Edit)
	* Click the Manage Call Center Users button
	* Click Add More Users button
	* Follow the instructions to filter users and click the Find button (Having agents in specific Profiles, Roles, Departments, etc.. helps with adding agents)
	* Select the users for this call center and click the Add to Call Center button

Classic:
    The above users will now see the Phone Icon in the Utility Bar (Bottom Right)

Lightning:
    Type app manager in the Setup Quick Find
	Click the Menu Link that appears for App Manager
	Edit a Lightning App that requires the Phone
	Click the Utility Bar under APP SETTINGS
	Search for Open CTI Softphone and click the utility bar item that appears
	Change Panel Width to 360
	Save
Agents will now have the Phone panel menu button on the bottom left
