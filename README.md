# big-data-project

## Part I Script
The part one script can be run by using the following command
```
spark-submit validation_script.py PATH-TO-FILE
```
where ```PATH-TO-FILE``` is the path to the input data csv file.
The outputs will be stored as partitioned text files in directories, with each directory representing one column named in the following convention:
col_```col_id```_```col_name```

The dataset is available for download at https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i

## Park II Data Analysis
Most of our work are done in the format of Jupyter Notebook using PySpark, Pandas, and a variety of other libraries for better visualization and easier understanding. To run these notebooks, we launched an EMR cluster with Spark build on AWS and set up notebook connection to the master node via the tutorial at https://aws.amazon.com/blogs/big-data/running-jupyter-notebook-and-jupyterhub-on-amazon-emr/. These notebooks can then be ran like your typical notebook with Internet connection.
