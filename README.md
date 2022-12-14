### This app automates the process of remote temperature setting in a container at a defined time.

## I. Running for the first time
  1. You need to install / update Python from python.org
  2. In Terminal navigate to where the app files are - command for navigating (mac/Windows/Linux) is 'cd FolderName'
  3. Install virtual environment managing tool - `python -m pip install pipenv`
  4. Initiate virtual environment - `pipenv shell`
  5. Install necessary packages - `pipenv sync`
  6. Provide program with Your login and password - `python app.py login`

## II. Standard operation
  1. Configure datetime, container and temperature to be set in **schedule.csv** file
  2. If the set datetime is in the past program will execute its task immediately after launching
  3. If there is no temperature given for a container program will ignore that row
  4. Launch Terminal app
  5. In Terminal navigate to where the app files are - command for navigating (mac/Windows/Linux) is `cd FolderName`
  6. Launch virtual environment - `pipenv shell`
  7. Launch program - `python app.py`
  8. You will be displayed container name, datetime and temperatures to be set
  
 ## III. Short version
  1. Set time, container and temperature in **schedule.csv**
  2. Launch Terminal in directory containing app
  3. Command `pipenv shell`
  4. Command `python app.py`
