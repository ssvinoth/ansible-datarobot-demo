0. Get user input:
    - Datarobot project name 
    - Data server from where the data will be collected
    - Data collection script which will be copied to the data server and gets executed.Data collection script will output the data into  /tmp directory
    - Data type of the input (csv,tsv,xls - allowed format in datarobot)

1. Copy the script and run the data collection script on the selected data server

2. Copy back the generated data file into controller.In this example controller host uploads the data hence copying the file into controller. This can be any host which has internet connection to datarobot)

3. Create project and initiate the data upload in `datarobot` using API

4. Check if the data has been uploaded and the project has been successfully created.
