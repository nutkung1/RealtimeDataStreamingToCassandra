# RealtimeDataStreamingToCassandra
*API Data Extraction: Personal data is retrieved from an external API.

* Apache Airflow manages the scheduling and orchestration of tasks across various stages, ensuring a smooth workflow from extraction to final storage.

* PostgreSQL A staging area for temporary storage before the data is processed and moved to the real-time integration pipeline.

* Apache Kafka is a real-time data streaming platform that integrates various data sources and passes the stream to processing systems.

* Apache ZooKeeper Coordinates and synchronizes configurations, acting as a mediator to maintain consistency and reliability across services and distributed systems.

* Apache Spark Computes the streaming data, performing real-time analysis or transformations as data flows through the pipeline.

* Cassandra Finally stores the processed data in a distributed, highly available, and scalable database, designed to handle large-scale data efficiently.
