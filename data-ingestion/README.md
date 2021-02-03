# Contoh Data Ingestion
MySQL to BigQuery DAG file for Cloud Composer (Airflow)

Prerequisite:
* Google Cloud Storage bucket created
* BigQuery dataset created
* Airflow installed locally. Install airflow `pip install "airflow[gcp,mysql]"`

How to:
* Run airflow webserver & scheduler
* Create a mysql connection on webserver under Admin > Connections
* Change values on the python file as commented
* Move the python file to dag folder
