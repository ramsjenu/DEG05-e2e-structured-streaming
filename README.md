# DEG05-e2e-structured-streaming

API --->   KAFKA Topic  -----> Cassandra Table

Functions:-
1) It fetches the data from the API https://randomuser.me/api/

2) It inserts the data into kafka topic : users_created

3) In Cassandra data is consumed

Actions:
1) Kafka Topic to be created "users_created"

2) In Airflow - "Users Automation" DAG to be envoked.

3) See the results in Cassandra
