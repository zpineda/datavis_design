## Studio 01 - Introduction to Tableau

This studio will provide an introduction to the interface, functionality, and visual capabilities of [Tableau Public](https://public.tableau.com/s/).

### Datasets

We will be using one dataset for this map:

* 311 Service Requests - Originally downloaded from [here](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/data)

### Gathering and preparing data
#### Downloading 311 Data from the NYC OpenData portal

* Navigate to the [NYC OpenData portal](https://opendata.cityofnewyork.us/).

![NYC OpenData](https://github.com/emilyfuhrman/datavis_design/blob/master/2017_Fall/Studios/Images/01/01_NYC_OpenData_Home.png)

* Click on the `Data` tab. Here you can explore different datasets by category, by popularity, or by recency. 
* Today we will be working with the NYC 311 dataset. 311 is the complaint hotline for New York City, and the available dataset records every call made to 311 since 2010. Type `311` in the search bar, and hit `Enter`. 
* Click on the first result, `311 Service Requests from 2010 to Present`.

![311 Main](https://github.com/emilyfuhrman/datavis_design/blob/master/2017_Fall/Studios/Images/01/02_311_Main.png)

* [Here](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9), you can see a great deal of information about this dataset: its attributes, its size, the frequency with which it is updated, its format. Scroll down to the `Table Preview` section to get a picture of what the data looks like in tabular format.

![311 Preview](https://github.com/emilyfuhrman/datavis_design/blob/master/2017_Fall/Studios/Images/01/03_311_Preview.png)

* Click `Explore Data`. Here, you can see the dataset in its entirety. You can also apply filters to the data to prepare it for download.

![311 Explore](https://github.com/emilyfuhrman/datavis_design/blob/master/2017_Fall/Studios/Images/01/04_311_Explore.png)

* On the right side of the page, you will see a `Filter` panel, with the `Filter` sub-section automatically selected. We will be using this section to isolate only complaints from the past week, to make the size of the dataset more manageable.
* Click the `Unique Key` field. This opens a menu containing all of the column headers in the dataset. 
* Select `Created Date`.
* Click the `is` dropdown menu, and select `is between`. Two fields, one for a start value and one for an end value, should automatically appear below.
* Click the first field to open a calendar picker. Navigate to and select October 9th, 2017.
* Click the second field to open a second calendar picker. Today's date should automatically be selected. Keep today's date.
* Once you click out of this view, the dataset on the left should update to contain only the rows to which the filters apply.

![311 Filter](https://github.com/emilyfuhrman/datavis_design/blob/master/2017_Fall/Studios/Images/01/05_Filter_Date.png)

* Now, click the blue `Export` button from the set of colorful buttons on the top right side of the table. Click `Download As > CSV`. This will download the filtered dataset in CSV format.
* Open up the downloaded CSV in Excel or Google Sheets. Before creating our visualization, we'll want to trim down the size of the dataset by deleting unnecessary columns.
* Delete all columns except the following:
	* `Unique Key`
	* `Created Date`
	* `Agency`
	* `Agency Name`
	* `Complaint Type`
	* `Descriptor`
	* `Incident Zip`
	* `Status`
	* `Borough`
	* `Latitude`
	* `Longitude`
* Your dataset should now look something like this:

![Excel](https://github.com/emilyfuhrman/datavis_design/blob/master/2017_Fall/Studios/Images/01/06_Excel.png)

### Importing data into Tableau

* If you have not already done so, download and install [Tableau Public](https://public.tableau.com/s/).
* Open Tableau Public.

![Tableau Landing Screen](https://github.com/emilyfuhrman/datavis_design/blob/master/2017_Fall/Studios/Images/01/07_Tableau_Landing_Screen.png)

* The first thing you see when you open Tableau is a screen with three sections: "Connect," "Open," and "Discover."
	* The "Connect" section enables us to connect different types of data into the workspace.
	* Since we have not saved any workbooks yet, the "Open" section is blank. 
	* "Discover" points us to a series of Tableau-provided resources.

### Pivoting

















