# Big-Data-Hadoop-and-Spark-Developer
BIG DATA / SCALA / HADOOP

Awesome Big Data
Awesome

A curated list of awesome big data frameworks, resources and other awesomeness. Inspired by awesome-php, awesome-python, awesome-ruby, hadoopecosystemtable & big-data.

Your contributions are always welcome!

Awesome Big Data
RDBMS
Frameworks
Distributed Programming
Distributed Filesystem
Key-Map Data Model
Document Data Model
Key-value Data Model
Graph Data Model
NewSQL Databases
Columnar Databases
Time-Series Databases
SQL-like processing
Data Ingestion
Service Programming
Scheduling
Machine Learning
Benchmarking
Security
System Deployment
Applications
Search engine and framework
MySQL forks and evolutions
PostgreSQL forks and evolutions
Memcached forks and evolutions
Embedded Databases
Business Intelligence
Data Visualization
Internet of things and sensor data
Interesting Readings
Interesting Papers
Videos
Books
Other Awesome Lists
RDBMS
MySQL The world's most popular open source database.
PostgreSQL The world's most advanced open source database.
Oracle Database - object-relational database management system.
Teradata - high-performance MPP data warehouse platform.
Frameworks
Bistro - general-purpose data processing engine for both batch and stream analytics. It is based on a novel data model, which represents data via functions and processes data via column operations as opposed to having only set operations in conventional approaches like MapReduce or SQL.
IBM Streams - platform for distributed processing and real-time analytics. Integrates with many of the popular technologies in the Big Data ecosystem (Kafka, HDFS, Spark, etc.)
Apache Hadoop - framework for distributed processing. Integrates MapReduce (parallel processing), YARN (job scheduling) and HDFS (distributed file system).
Tigon - High Throughput Real-time Stream Processing Framework.
Pachyderm - Pachyderm is a data storage platform built on Docker and Kubernetes to provide reproducible data processing and analysis.
Polyaxon - A platform for reproducible and scalable machine learning and deep learning.
Distributed Programming
AddThis Hydra - distributed data processing and storage system originally developed at AddThis.
AMPLab SIMR - run Spark on Hadoop MapReduce v1.
Apache APEX - a unified, enterprise platform for big data stream and batch processing.
Apache Beam - an unified model and set of language-specific SDKs for defining and executing data processing workflows.
Apache Crunch - a simple Java API for tasks like joining and data aggregation that are tedious to implement on plain MapReduce.
Apache DataFu - collection of user-defined functions for Hadoop and Pig developed by LinkedIn.
Apache Flink - high-performance runtime, and automatic program optimization.
Apache Gearpump - real-time big data streaming engine based on Akka.
Apache Gora - framework for in-memory data model and persistence.
Apache Hama - BSP (Bulk Synchronous Parallel) computing framework.
Apache MapReduce - programming model for processing large data sets with a parallel, distributed algorithm on a cluster.
Apache Pig - high level language to express data analysis programs for Hadoop.
Apache REEF - retainable evaluator execution framework to simplify and unify the lower layers of big data systems.
Apache S4 - framework for stream processing, implementation of S4.
Apache Spark - framework for in-memory cluster computing.
Apache Spark Streaming - framework for stream processing, part of Spark.
Apache Storm - framework for stream processing by Twitter also on YARN.
Apache Samza - stream processing framework, based on Kafka and YARN.
Apache Tez - application framework for executing a complex DAG (directed acyclic graph) of tasks, built on YARN.
Apache Twill - abstraction over YARN that reduces the complexity of developing distributed applications.
Baidu Bigflow - an interface that allows for writing distributed computing programs providing lots of simple, flexible, powerful APIs to easily handle data of any scale.
Cascalog - data processing and querying library.
Cheetah - High Performance, Custom Data Warehouse on Top of MapReduce.
Concurrent Cascading - framework for data management/analytics on Hadoop.
Damballa Parkour - MapReduce library for Clojure.
Datasalt Pangool - alternative MapReduce paradigm.
DataTorrent StrAM - real-time engine is designed to enable distributed, asynchronous, real time in-memory big-data computations in as unblocked a way as possible, with minimal overhead and impact on performance.
Facebook Corona - Hadoop enhancement which removes single point of failure.
Facebook Peregrine - Map Reduce framework.
Facebook Scuba - distributed in-memory datastore.
Google Dataflow - create data pipelines to help themæingest, transform and analyze data.
Google MapReduce - map reduce framework.
Google MillWheel - fault tolerant stream processing framework.
IBM Streams - platform for distributed processing and real-time analytics. Provides toolkits for advanced analytics like geospatial, time series, etc. out of the box.
JAQL - declarative programming language for working with structured, semi-structured and unstructured data.
Kite - is a set of libraries, tools, examples, and documentation focused on making it easier to build systems on top of the Hadoop ecosystem.
Metamarkets Druid - framework for real-time analysis of large datasets.
Netflix PigPen - map-reduce for Clojure which compiles to Apache Pig.
Nokia Disco - MapReduce framework developed by Nokia.
Onyx - Distributed computation for the cloud.
Pinterest Pinlater - asynchronous job execution system.
Pydoop - Python MapReduce and HDFS API for Hadoop.
Ray - A fast and simple framework for building and running distributed applications.
Rackerlabs Blueflood - multi-tenant distributed metric processing system
Skale - High performance distributed data processing in NodeJS.
Stratosphere - general purpose cluster computing framework.
Streamdrill - useful for counting activities of event streams over different time windows and finding the most active one.
streamsx.topology - Libraries to enable building IBM Streams application in Java, Python or Scala.
Tuktu - Easy-to-use platform for batch and streaming computation, built using Scala, Akka and Play!
Twitter Heron - Heron is a realtime, distributed, fault-tolerant stream processing engine from Twitter replacing Storm.
Twitter Scalding - Scala library for Map Reduce jobs, built on Cascading.
Twitter Summingbird - Streaming MapReduce with Scalding and Storm, by Twitter.
Twitter TSAR - TimeSeries AggregatoR by Twitter.
Wallaroo - The ultrafast and elastic data processing engine. Big or fast data - no fuss, no Java needed.
Distributed Filesystem
Ambry - a distributed object store that supports storage of trillion of small immutable objects as well as billions of large objects.
Apache HDFS - a way to store large files across multiple machines.
Apache Kudu - Hadoop's storage layer to enable fast analytics on fast data.
BeeGFS - formerly FhGFS, parallel distributed file system.
Ceph Filesystem - software storage platform designed.
Disco DDFS - distributed filesystem.
Facebook Haystack - object storage system.
Google Colossus - distributed filesystem (GFS2).
Google GFS - distributed filesystem.
Google Megastore - scalable, highly available storage.
GridGain - GGFS, Hadoop compliant in-memory file system.
Lustre file system - high-performance distributed filesystem.
Microsoft Azure Data Lake Store - HDFS-compatible storage in Azure cloud
Quantcast File System QFS - open-source distributed file system.
Red Hat GlusterFS - scale-out network-attached storage file system.
Seaweed-FS - simple and highly scalable distributed file system.
Alluxio - reliable file sharing at memory speed across cluster frameworks.
Tahoe-LAFS - decentralized cloud storage system.
Baidu File System - distributed filesystem.
Distributed Index
Pilosa Open source distributed bitmap index that dramatically accelerates queries across multiple, massive data sets.
Document Data Model
Actian Versant - commercial object-oriented database management systems .
Crate Data - is an open source massively scalable data store. It requires zero administration.
Facebook Apollo - Facebook’s Paxos-like NoSQL database.
jumboDB - document oriented datastore over Hadoop.
LinkedIn Espresso - horizontally scalable document-oriented NoSQL data store.
MarkLogic - Schema-agnostic Enterprise NoSQL database technology.
Microsoft Azure DocumentDB - NoSQL cloud database service with protocol support for MongoDB
MongoDB - Document-oriented database system.
RavenDB - A transactional, open-source Document Database.
RethinkDB - document database that supports queries like table joins and group by.
Key Map Data Model
Note: There is some term confusion in the industry, and two different things are called "Columnar Databases". Some, listed here, are distributed, persistent databases built around the "key-map" data model: all data has a (possibly composite) key, with which a map of key-value pairs is associated. In some systems, multiple such value maps can be associated with a key, and these maps are referred to as "column families" (with value map keys being referred to as "columns").

Another group of technologies that can also be called "columnar databases" is distinguished by how it stores data, on disk or in memory -- rather than storing data the traditional way, where all column values for a given key are stored next to each other, "row by row", these systems store all column values next to each other. So more work is needed to get all columns for a given key, but less work is needed to get all values for a given column.

The former group is referred to as "key map data model" here. The line between these and the Key-value Data Model stores is fairly blurry.

The latter, being more about the storage format than about the data model, is listed under Columnar Databases.

You can read more about this distinction on Prof. Daniel Abadi's blog: Distinguishing two major types of Column Stores.

Apache Accumulo - distributed key/value store, built on Hadoop.
Apache Cassandra - column-oriented distributed datastore, inspired by BigTable.
Apache HBase - column-oriented distributed datastore, inspired by BigTable.
Baidu Tera - an Internet-scale database, inspired by BigTable.
Facebook HydraBase - evolution of HBase made by Facebook.
Google BigTable - column-oriented distributed datastore.
Google Cloud Datastore - is a fully managed, schemaless database for storing non-relational data over BigTable.
Hypertable - column-oriented distributed datastore, inspired by BigTable.
InfiniDB - is accessed through a MySQL interface and use massive parallel processing to parallelize queries.
Tephra - Transactions for HBase.
Twitter Manhattan - real-time, multi-tenant distributed database for Twitter scale.
ScyllaDB - column-oriented distributed datastore written in C++, totally compatible with Apache Cassandra.
Key-value Data Model
Aerospike - NoSQL flash-optimized, in-memory. Open source and "Server code in 'C' (not Java or Erlang) precisely tuned to avoid context switching and memory copies."
Amazon DynamoDB - distributed key/value store, implementation of Dynamo paper.
Badger - a fast, simple, efficient, and persistent key-value store written natively in Go.
Bolt - an embedded key-value database for Go.
BTDB - Key Value Database in .Net with Object DB Layer, RPC, dynamic IL and much more
BuntDB - a fast, embeddable, in-memory key/value database for Go with custom indexing and geospatial support.
Edis - is a protocol-compatible Server replacement for Redis.
ElephantDB - Distributed database specialized in exporting data from Hadoop.
EventStore - distributed time series database.
GridDB - suitable for sensor data stored in a timeseries.
HyperDex - a scalable, next generation key-value and document store with a wide array of features, including consistency, fault tolerance and high performance.
Ignite - is an in-memory key-value data store providing full SQL-compliant data access that can optionally be backed by disk storage.
LinkedIn Krati - is a simple persistent data store with very low latency and high throughput.
Linkedin Voldemort - distributed key/value storage system.
Oracle NoSQL Database - distributed key-value database by Oracle Corporation.
Redis - in memory key value datastore.
Riak - a decentralized datastore.
Storehaus - library to work with asynchronous key value stores, by Twitter.
SummitDB - an in-memory, NoSQL key/value database, with disk persistance and using the Raft consensus algorithm.
Tarantool - an efficient NoSQL database and a Lua application server.
TiKV - a distributed key-value database powered by Rust and inspired by Google Spanner and HBase.
Tile38 - a geolocation data store, spatial index, and realtime geofence, supporting a variety of object types including latitude/longitude points, bounding boxes, XYZ tiles, Geohashes, and GeoJSON
TreodeDB - key-value store that's replicated and sharded and provides atomic multirow writes.
Graph Data Model
AgensGraph - a new generation multi-model graph database for the modern complex data environment.
Apache Giraph - implementation of Pregel, based on Hadoop.
Apache Spark Bagel - implementation of Pregel, part of Spark.
ArangoDB - multi model distributed database.
DGraph - A scalable, distributed, low latency, high throughput graph database aimed at providing Google production level scale and throughput, with low enough latency to be serving real time user queries, over terabytes of structured data.
EliasDB - a lightweight graph based database that does not require any third-party libraries.
Facebook TAO - TAO is the distributed data store that is widely used at facebook to store and serve the social graph.
GCHQ Gaffer - Gaffer by GCHQ is a framework that makes it easy to store large-scale graphs in which the nodes and edges have statistics.
Google Cayley - open-source graph database.
Google Pregel - graph processing framework.
GraphLab PowerGraph - a core C++ GraphLab API and a collection of high-performance machine learning and data mining toolkits built on top of the GraphLab API.
GraphX - resilient Distributed Graph System on Spark.
Gremlin - graph traversal Language.
Infovore - RDF-centric Map/Reduce framework.
Intel GraphBuilder - tools to construct large-scale graphs on top of Hadoop.
JanusGraph - open-source, distributed graph database with multiple options for storage backends (Bigtable, HBase, Cassandra, etc.) and indexing backends (Elasticsearch, Solr, Lucene).
MapGraph - Massively Parallel Graph processing on GPUs.
Microsoft Graph Engine - a distributed in-memory data processing engine, underpinned by a strongly-typed in-memory key-value store and a general distributed computation engine.
Neo4j - graph database written entirely in Java.
OrientDB - document and graph database.
Phoebus - framework for large scale graph processing.
Titan - distributed graph database, built over Cassandra.
Twitter FlockDB - distributed graph database.
NodeXL - A free, open-source template for Microsoft® Excel® 2007, 2010, 2013 and 2016 that makes it easy to explore network graphs.
Columnar Databases
Note please read the note on Key-Map Data Model section.

Columnar Storage - an explanation of what columnar storage is and when you might want it.
Actian Vector - column-oriented analytic database.
C-Store - column oriented DBMS.
ClickHouse - an open-source column-oriented database management system that allows generating analytical data reports in real time.
EventQL - a distributed, column-oriented database built for large-scale event collection and analytics.
MonetDB - column store database.
Parquet - columnar storage format for Hadoop.
Pivotal Greenplum - purpose-built, dedicated analytic data warehouse that offers a columnar engine as well as a traditional row-based one.
Vertica - is designed to manage large, fast-growing volumes of data and provide very fast query performance when used for data warehouses.
SQream DB - A GPU powered big data database, designed for analytics and data warehousing, with ANSI-92 compliant SQL, suitable for data sets from 10TB to 1PB.
Google BigQuery - Google's cloud offering backed by their pioneering work on Dremel.
Amazon Redshift - Amazon's cloud offering, also based on a columnar datastore backend.
IndexR - an open-source columnar storage format for fast & realtime analytic with big data.
LocustDB - an experimental analytics database aiming to set a new standard for query performance on commodity hardware.
NewSQL Databases
Actian Ingres - commercially supported, open-source SQL relational database management system.
ActorDB - a distributed SQL database with the scalability of a KV store, while keeping the query capabilities of a relational database.
Amazon RedShift - data warehouse service, based on PostgreSQL.
BayesDB - statistic oriented SQL database.
Bedrock - a simple, modular, networked and distributed transaction layer built atop SQLite.
CitusDB - scales out PostgreSQL through sharding and replication.
Cockroach - Scalable, Geo-Replicated, Transactional Datastore.
Comdb2 - a clustered RDBMS built on optimistic concurrency control techniques.
Datomic - distributed database designed to enable scalable, flexible and intelligent applications.
FoundationDB - distributed database, inspired by F1.
Google F1 - distributed SQL database built on Spanner.
Google Spanner - globally distributed semi-relational database.
H-Store - is an experimental main-memory, parallel database management system that is optimized for on-line transaction processing (OLTP) applications.
Haeinsa - linearly scalable multi-row, multi-table transaction library for HBase based on Percolator.
HandlerSocket - NoSQL plugin for MySQL/MariaDB.
InfiniSQL - infinity scalable RDBMS.
Map-D - GPU in-memory database, big data analysis and visualization platform.
MemSQL - in memory SQL database witho optimized columnar storage on flash.
NuoDB - SQL/ACID compliant distributed database.
Oracle TimesTen in-Memory Database - in-memory, relational database management system with persistence and recoverability.
Pivotal GemFire XD - Low-latency, in-memory, distributed SQL data store. Provides SQL interface to in-memory table data, persistable in HDFS.
SAP HANA - is an in-memory, column-oriented, relational database management system.
SenseiDB - distributed, realtime, semi-structured database.
Sky - database used for flexible, high performance analysis of behavioral data.
SymmetricDS - open source software for both file and database synchronization.
TiDB - TiDB is a distributed SQL database. Inspired by the design of Google F1.
VoltDB - claims to be fastest in-memory database.
Time-Series Databases
Axibase Time Series Database - Integrated time series database on top of HBase with built-in visualization, rule-engine and SQL support.
Chronix - a time series storage built to store time series highly compressed and for fast access times.
Cube - uses MongoDB to store time series data.
Heroic - is a scalable time series database based on Cassandra and Elasticsearch.
InfluxDB - distributed time series database.
IronDB - scalable, general-purpose time series database.
Kairosdb - similar to OpenTSDB but allows for Cassandra.
M3DB - a distributed time series database that can be used for storing realtime metrics at long retention.
Newts - a time series database based on Apache Cassandra.
OpenTSDB - distributed time series database on top of HBase.
Prometheus - a time series database and service monitoring system.
Beringei - Facebook's in-memory time-series database.
TrailDB - an efficient tool for storing and querying series of events.
Druid Column oriented distributed data store ideal for powering interactive applications
Riak-TS Riak TS is the only enterprise-grade NoSQL time series database optimized specifically for IoT and Time Series data.
Akumuli Akumuli is a numeric time-series database. It can be used to capture, store and process time-series data in real-time. The word "akumuli" can be translated from esperanto as "accumulate".
Rhombus A time-series object store for Cassandra that handles all the complexity of building wide row indexes.
Dalmatiner DB Fast distributed metrics database
Blueflood A distributed system designed to ingest and process time series data
Timely Timely is a time series database application that provides secure access to time series data based on Accumulo and Grafana.
SiriDB Highly-scalable, robust and fast, open source time series database with cluster functionality.
Thanos - Thanos is a set of components to create a highly available metric system with unlimited storage capacity using multiple (existing) Prometheus deployments.
VictoriaMetrics - fast, scalable and resource-effective open-source TSDB compatible with Prometheus. Single-node and cluster versions included
SQL-like processing
Actian SQL for Hadoop - high performance interactive SQL access to all Hadoop data.
Apache Drill - framework for interactive analysis, inspired by Dremel.
Apache HCatalog - table and storage management layer for Hadoop.
Apache Hive - SQL-like data warehouse system for Hadoop.
Apache Calcite - framework that allows efficient translation of queries involving heterogeneous and federated data.
Apache Phoenix - SQL skin over HBase.
Aster Database - SQL-like analytic processing for MapReduce.
Cloudera Impala - framework for interactive analysis, Inspired by Dremel.
Concurrent Lingual - SQL-like query language for Cascading.
Datasalt Splout SQL - full SQL query engine for big datasets.
Dremio - an open-source, SQL-like Data-as-a-Service Platform based on Apache Arrow.
Facebook PrestoDB - distributed SQL query engine.
Google BigQuery - framework for interactive analysis, implementation of Dremel.
PipelineDB - an open-source relational database that runs SQL queries continuously on streams, incrementally storing results in tables.
Pivotal HDB - SQL-like data warehouse system for Hadoop.
RainstorDB - database for storing petabyte-scale volumes of structured and semi-structured data.
Spark Catalyst - is a Query Optimization Framework for Spark and Shark.
SparkSQL - Manipulating Structured Data Using Spark.
Splice Machine - a full-featured SQL-on-Hadoop RDBMS with ACID transactions.
Stinger - interactive query for Hive.
Tajo - distributed data warehouse system on Hadoop.
Trafodion - enterprise-class SQL-on-HBase solution targeting big data transactional or operational workloads.
Data Ingestion
Amazon Kinesis - real-time processing of streaming data at massive scale.
Amazon Web Services Glue - serverless fully managed extract, transform, and load (ETL) service
Apache Chukwa - data collection system.
Apache Flume - service to manage large amount of log data.
Apache Kafka - distributed publish-subscribe messaging system.
Apache NiFi - Apache NiFi is an integrated data logistics platform for automating the movement of data between disparate systems.
Apache Sqoop - tool to transfer data between Hadoop and a structured datastore.
Cloudera Morphlines - framework that help ETL to Solr, HBase and HDFS.
Embulk - open-source bulk data loader that helps data transfer between various databases, storages, file formats, and cloud services.
Facebook Scribe - streamed log data aggregator.
Fluentd - tool to collect events and logs.
Google Photon - geographically distributed system for joining multiple continuously flowing streams of data in real-time with high scalability and low latency.
Heka - open source stream processing software system.
HIHO - framework for connecting disparate data sources with Hadoop.
Kestrel - distributed message queue system.
LinkedIn Databus - stream of change capture events for a database.
LinkedIn Kamikaze - utility package for compressing sorted integer arrays.
LinkedIn White Elephant - log aggregator and dashboard.
Logstash - a tool for managing events and logs.
Netflix Suro - log agregattor like Storm and Samza based on Chukwa.
Pinterest Secor - is a service implementing Kafka log persistance.
Linkedin Gobblin - linkedin's universal data ingestion framework.
Skizze - sketch data store to deal with all problems around counting and sketching using probabilistic data-structures.
StreamSets Data Collector - continuous big data ingest infrastructure with a simple to use IDE.
Yahoo Pulsar - a distributed pub-sub messaging platform with a very flexible messaging model and an intuitive client API.
Alooma - data pipeline as a service enabling moving data sources such as MySQL into data warehouses.
Service Programming
Akka Toolkit - runtime for distributed, and fault tolerant event-driven applications on the JVM.
Apache Avro - data serialization system.
Apache Curator - Java libaries for Apache ZooKeeper.
Apache Karaf - OSGi runtime that runs on top of any OSGi framework.
Apache Thrift - framework to build binary protocols.
Apache Zookeeper - centralized service for process management.
Google Chubby - a lock service for loosely-coupled distributed systems.
Hydrosphere Mist - a service for exposing Apache Spark analytics jobs and machine learning models as realtime, batch or reactive web services.
Linkedin Norbert - cluster manager.
Mara - A lightweight opinionated ETL framework, halfway between plain scripts and Apache Airflow
OpenMPI - message passing framework.
Serf - decentralized solution for service discovery and orchestration.
Spotify Luigi - a Python package for building complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization, handling failures, command line integration, and much more.
Spring XD - distributed and extensible system for data ingestion, real time analytics, batch processing, and data export.
Twitter Elephant Bird - libraries for working with LZOP-compressed data.
Twitter Finagle - asynchronous network stack for the JVM.
Scheduling
Apache Airflow - a platform to programmatically author, schedule and monitor workflows.
Apache Aurora - is a service scheduler that runs on top of Apache Mesos.
Apache Falcon - data management framework.
Apache Oozie - workflow job scheduler.
Azure Data Factory - cloud-based pipeline orchestration for on-prem, cloud and HDInsight
Chronos - distributed and fault-tolerant scheduler.
Linkedin Azkaban - batch workflow job scheduler.
Schedoscope - Scala DSL for agile scheduling of Hadoop jobs.
Sparrow - scheduling platform.
Machine Learning
Azure ML Studio - Cloud-based AzureML, R, Python Machine Learning platform
brain - Neural networks in JavaScript.
Cloudera Oryx - real-time large-scale machine learning.
Concurrent Pattern - machine learning library for Cascading.
convnetjs - Deep Learning in Javascript. Train Convolutional Neural Networks (or ordinary ones) in your browser.
DataVec - A vectorization and data preprocessing library for deep learning in Java and Scala. Part of the Deeplearning4j ecosystem.
Deeplearning4j - Fast, open deep learning for the JVM (Java, Scala, Clojure). A neural network configuration layer powered by a C++ library. Uses Spark and Hadoop to train nets on multiple GPUs and CPUs.
Decider - Flexible and Extensible Machine Learning in Ruby.
ENCOG - machine learning framework that supports a variety of advanced algorithms, as well as support classes to normalize and process data.
etcML - text classification with machine learning.
Etsy Conjecture - scalable Machine Learning in Scalding.
Feast - A feature store for the management, discovery, and access of machine learning features. Feast provides a consistent view of feature data for both model training and model serving.
GraphLab Create - A machine learning platform in Python with a broad collection of ML toolkits, data engineering, and deployment tools.
H2O - statistical, machine learning and math runtime with Hadoop. R and Python.
Keras - An intuitive neural net API inspired by Torch that runs atop Theano and Tensorflow.
Lambdo is a workflow engine which significantly simplifies data processing and analysis by combining in one analysis pipeline (i) feature engineering and machine learning (ii) model training and prediction (iii) table population and column evaluation via user-defined (Python) functions.
Mahout - An Apache-backed machine learning library for Hadoop.
MLbase - distributed machine learning libraries for the BDAS stack.
MLPNeuralNet - Fast multilayer perceptron neural network library for iOS and Mac OS X.
ML Workspace - All-in-one web-based IDE specialized for machine learning and data science.
MOA - MOA performs big data stream mining in real time, and large scale machine learning.
MonkeyLearn - Text mining made easy. Extract and classify data from text.
ND4J - A matrix library for the JVM. Numpy for Java.
nupic - Numenta Platform for Intelligent Computing: a brain-inspired machine intelligence platform, and biologically accurate neural network based on cortical learning algorithms.
PredictionIO - machine learning server buit on Hadoop, Mahout and Cascading.
RL4J - Reinforcement learning for Java and Scala. Includes Deep-Q learning and A3C algorithms, and integrates with Open AI's Gym. Runs in the Deeplearning4j ecosystem.
SAMOA - distributed streaming machine learning framework.
scikit-learn - scikit-learn: machine learning in Python.
Spark MLlib - a Spark implementation of some common machine learning (ML) functionality.
Sibyl - System for Large Scale Machine Learning at Google.
TensorFlow - Library from Google for machine learning using data flow graphs.
Theano - A Python-focused machine learning library supported by the University of Montreal.
Torch - A deep learning library with a Lua API, supported by NYU and Facebook.
Velox - System for serving machine learning predictions.
Vowpal Wabbit - learning system sponsored by Microsoft and Yahoo!.
WEKA - suite of machine learning software.
BidMach - CPU and GPU-accelerated Machine Learning Library.
Benchmarking
Apache Hadoop Benchmarking - micro-benchmarks for testing Hadoop performances.
Berkeley SWIM Benchmark - real-world big data workload benchmark.
Intel HiBench - a Hadoop benchmark suite.
PUMA Benchmarking - benchmark suite for MapReduce applications.
Yahoo Gridmix3 - Hadoop cluster benchmarking from Yahoo engineer team.
Deeplearning4j Benchmarks
Security
Apache Ranger - Central security admin & fine-grained authorization for Hadoop
Apache Eagle - real time monitoring solution
Apache Knox Gateway - single point of secure access for Hadoop clusters.
Apache Sentry - security module for data stored in Hadoop.
BDA - The vulnerability detector for Hadoop and Spark
System Deployment
Apache Ambari - operational framework for Hadoop mangement.
Apache Bigtop - system deployment framework for the Hadoop ecosystem.
Apache Helix - cluster management framework.
Apache Mesos - cluster manager.
Apache Slider - is a YARN application to deploy existing distributed applications on YARN.
Apache Whirr - set of libraries for running cloud services.
Apache YARN - Cluster manager.
Brooklyn - library that simplifies application deployment and management.
Buildoop - Similar to Apache BigTop based on Groovy language.
Cloudera HUE - web application for interacting with Hadoop.
Facebook Prism - multi datacenters replication system.
Google Borg - job scheduling and monitoring system.
Google Omega - job scheduling and monitoring system.
Hortonworks HOYA - application that can deploy HBase cluster on YARN.
Kubernetes - a system for automating deployment, scaling, and management of containerized applications.
Marathon - Mesos framework for long-running services.
Applications
411 - an web application for alert management resulting from scheduled searches into Elasticsearch.
Adobe spindle - Next-generation web analytics processing with Scala, Spark, and Parquet.
Apache Kiji - framework to collect and analyze data in real-time, based on HBase.
Apache Metron - a platform that integrates a variety of open source big data technologies in order to offer a centralized tool for security monitoring and analysis.
Apache Nutch - open source web crawler.
Apache OODT - capturing, processing and sharing of data for NASA's scientific archives.
Apache Tika - content analysis toolkit.
Argus - Time series monitoring and alerting platform.
AthenaX - a streaming analytics platform that enables users to run production-quality, large scale streaming analytics using Structured Query Language (SQL).
Atlas - a backend for managing dimensional time series data.
Countly - open source mobile and web analytics platform, based on Node.js & MongoDB.
Domino - Run, scale, share, and deploy models — without any infrastructure.
Eclipse BIRT - Eclipse-based reporting system.
ElastAert - ElastAlert is a simple framework for alerting on anomalies, spikes, or other patterns of interest from data in ElasticSearch.
Eventhub - open source event analytics platform.
Hermes - asynchronous message broker built on top of Kafka.
HIPI Library - API for performing image processing tasks on Hadoop's MapReduce.
Hunk - Splunk analytics for Hadoop.
Imhotep - Large scale analytics platform by indeed.
Indicative - Web & mobile analytics tool, with data warehouse (AWS, BigQuery) integration.
Jupyter - Notebook and project application for interactive data science and scientific computing across all programming languages.
MADlib - data-processing library of an RDBMS to analyze data.
Kapacitor - an open source framework for processing, monitoring, and alerting on time series data.
Kylin - open source Distributed Analytics Engine from eBay.
PivotalR - R on Pivotal HD / HAWQ and PostgreSQL.
Rakam - open-source real-time custom analytics platform powered by Postgresql, Kinesis and PrestoDB.
Qubole - auto-scaling Hadoop cluster, built-in data connectors.
Sense - Cloud Platform for Data Science and Big Data Analytics.
SnappyData - a distributed in-memory data store for real-time operational analytics, delivering stream analytics, OLTP (online transaction processing) and OLAP (online analytical processing) built on Spark in a single integrated cluster.
Snowplow - enterprise-strength web and event analytics, powered by Hadoop, Kinesis, Redshift and Postgres.
SparkR - R frontend for Spark.
Splunk - analyzer for machine-generated data.
Sumo Logic - cloud based analyzer for machine-generated data.
Talend - unified open source environment for YARN, Hadoop, HBASE, Hive, HCatalog & Pig.
Warp - query by example tool for big data (OS X app)
Search engine and framework
Apache Lucene - Search engine library.
Apache Solr - Search platform for Apache Lucene.
Elassandra - is a fork of Elasticsearch modified to run on top of Apache Cassandra in a scalable and resilient peer-to-peer architecture.
ElasticSearch - Search and analytics engine based on Apache Lucene.
Enigma.io – Freemium robust web application for exploring, filtering, analyzing, searching and exporting massive datasets scraped from across the Web.
Facebook Unicorn - social graph search platform.
Google Caffeine - continuous indexing system.
Google Percolator - continuous indexing system.
TeraGoogle - large search index.
HBase Coprocessor - implementation of Percolator, part of HBase.
Lily HBase Indexer - quickly and easily search for any content stored in HBase.
LinkedIn Bobo - is a Faceted Search implementation written purely in Java, an extension to Apache Lucene.
LinkedIn Cleo - is a flexible software library for enabling rapid development of partial, out-of-order and real-time typeahead search.
LinkedIn Galene - search architecture at LinkedIn.
LinkedIn Zoie - is a realtime search/indexing system written in Java.
MG4J - MG4J (Managing Gigabytes for Java) is a full-text search engine for large document collections written in Java. It is highly customisable, high-performance and provides state-of-the-art features and new research algorithms.
Sphinx Search Server - fulltext search engine.
Vespa - is an engine for low-latency computation over large data sets. It stores and indexes your data such that queries, selection and processing over the data can be performed at serving time.
Facebook Faiss - is a library for efficient similarity search and clustering of dense vectors. It contains algorithms that search in sets of vectors of any size, up to ones that possibly do not fit in RAM. It also contains supporting code for evaluation and parameter tuning. Faiss is written in C++ with complete wrappers for Python/numpy.
Annoy - is a C++ library with Python bindings to search for points in space that are close to a given query point. It also creates large read-only file-based data structures that are mmapped into memory so that many processes may share the same data.
MySQL forks and evolutions
Amazon RDS - MySQL databases in Amazon's cloud.
Drizzle - evolution of MySQL 6.0.
Google Cloud SQL - MySQL databases in Google's cloud.
MariaDB - enhanced, drop-in replacement for MySQL.
MySQL Cluster - MySQL implementation using NDB Cluster storage engine.
Percona Server - enhanced, drop-in replacement for MySQL.
ProxySQL - High Performance Proxy for MySQL.
TokuDB - TokuDB is a storage engine for MySQL and MariaDB.
WebScaleSQL - is a collaboration among engineers from several companies that face similar challenges in running MySQL at scale.
PostgreSQL forks and evolutions
HadoopDB - hybrid of MapReduce and DBMS.
IBM Netezza - high-performance data warehouse appliances.
Postgres-XL - Scalable Open Source PostgreSQL-based Database Cluster.
RecDB - Open Source Recommendation Engine Built Entirely Inside PostgreSQL.
Stado - open source MPP database system solely targeted at data warehousing and data mart applications.
Yahoo Everest - multi-peta-byte database / MPP derived by PostgreSQL.
TimescaleDB - An open-source time-series database optimized for fast ingest and complex queries
PipelineDB - The Streaming SQL Database. An open-source relational database that runs SQL queries continuously on streams, incrementally storing results in tables
Memcached forks and evolutions
Facebook McDipper - key/value cache for flash storage.
Facebook Memcached - fork of Memcache.
Twemproxy - A fast, light-weight proxy for memcached and redis.
Twitter Fatcache - key/value cache for flash storage.
Twitter Twemcache - fork of Memcache.
Embedded Databases
Actian PSQL - ACID-compliant DBMS developed by Pervasive Software, optimized for embedding in applications.
BerkeleyDB - a software library that provides a high-performance embedded database for key/value data.
HanoiDB - Erlang LSM BTree Storage.
LevelDB - a fast key-value storage library written at Google that provides an ordered mapping from string keys to string values.
LMDB - ultra-fast, ultra-compact key-value embedded data store developed by Symas.
RocksDB - embeddable persistent key-value store for fast storage based on LevelDB.
Business Intelligence
BIME Analytics - business intelligence platform in the cloud.
Blazer - business intelligence made simple.
Chartio - lean business intelligence platform to visualize and explore your data.
datapine - self-service business intelligence tool in the cloud.
GoodData - platform for data products and embedded analytics.
Jaspersoft - powerful business intelligence suite.
Jedox Palo - customisable Business Intelligence platform.
Jethrodata - Interactive Big Data Analytics.
intermix.io - Performance Monitoring for Amazon Redshift
Metabase - The simplest, fastest way to get business intelligence and analytics to everyone in your company.
Microsoft - business intelligence software and platform.
Microstrategy - software platforms for business intelligence, mobile intelligence, and network applications.
Numeracy - Fast, clean SQL client and business intelligence.
Pentaho - business intelligence platform.
Qlik - business intelligence and analytics platform.
Redash - Open source business intelligence platform, supporting multiple data sources and planned queries.
Saiku - open source analytics platform.
Knowage - open source business intelligence platform. (former SpagoBi)
SparklineData SNAP - modern B.I platform powered by Apache Spark.
Tableau - business intelligence platform.
Zoomdata - Big Data Analytics.
Data Visualization
Airpal - Web UI for PrestoDB.
AnyChart - fast, simple and flexible JavaScript (HTML5) charting library featuring pure JS API.
Arbor - graph visualization library using web workers and jQuery.
Banana - visualize logs and time-stamped data stored in Solr. Port of Kibana.
Bloomery - Web UI for Impala.
Bokeh - A powerful Python interactive visualization library that targets modern web browsers for presentation, with the goal of providing elegant, concise construction of novel graphics in the style of D3.js, but also delivering this capability with high-performance interactivity over very large or streaming datasets.
C3 - D3-based reusable chart library
CartoDB - open-source or freemium hosting for geospatial databases with powerful front-end editing capabilities and a robust API.
chartd - responsive, retina-compatible charts with just an img tag.
Chart.js - open source HTML5 Charts visualizations.
Chartist.js - another open source HTML5 Charts visualization.
Crossfilter - JavaScript library for exploring large multivariate datasets in the browser. Works well with dc.js and d3.js.
Cubism - JavaScript library for time series visualization.
Cytoscape - JavaScript library for visualizing complex networks.
DC.js - Dimensional charting built to work natively with crossfilter rendered using d3.js. Excellent for connecting charts/additional metadata to hover events in D3.
D3 - javaScript library for manipulating documents.
D3.compose - Compose complex, data-driven visualizations from reusable charts and components.
D3Plus - A fairly robust set of reusable charts and styles for d3.js.
DevExtreme React Chart - High-performance plugin-based React chart for Bootstrap and Material Design.
Echarts - Baidus enterprise charts.
Envisionjs - dynamic HTML5 visualization.
FnordMetric - write SQL queries that return SVG charts rather than tables
Frappe Charts - GitHub-inspired simple and modern SVG charts for the web with zero dependencies.
Freeboard - pen source real-time dashboard builder for IOT and other web mashups.
Gephi - An award-winning open-source platform for visualizing and manipulating large graphs and network connections. It's like Photoshop, but for graphs. Available for Windows and Mac OS X.
Google Charts - simple charting API.
Grafana - graphite dashboard frontend, editor and graph composer.
Graphite - scalable Realtime Graphing.
Highcharts - simple and flexible charting API.
IPython - provides a rich architecture for interactive computing.
Kibana - visualize logs and time-stamped data
Lumify - open source big data analysis and visualization platform
Matplotlib - plotting with Python.
Metricsgraphic.js - a library built on top of D3 that is optimized for time-series data
NVD3 - chart components for d3.js.
Peity - Progressive SVG bar, line and pie charts.
Plot.ly - Easy-to-use web service that allows for rapid creation of complex charts, from heatmaps to histograms. Upload data to create and style charts with Plotly's online spreadsheet. Fork others' plots.
Plotly.js The open source javascript graphing library that powers plotly.
Recline - simple but powerful library for building data applications in pure Javascript and HTML.
Redash - open-source platform to query and visualize data.
ReCharts - A composable charting library built on React components
Shiny - a web application framework for R.
Sigma.js - JavaScript library dedicated to graph drawing.
Superset - a data exploration platform designed to be visual, intuitive and interactive, making it easy to slice, dice and visualize data and perform analytics at the speed of thought.
Vega - a visualization grammar.
Zeppelin - a notebook-style collaborative data analysis.
Zing Charts - JavaScript charting library for big data.
Internet of things and sensor data
Apache Edgent (Incubating) - a programming model and micro-kernel style runtime that can be embedded in gateways and small footprint edge devices enabling local, real-time, analytics on the edge devices.
Azure IoT Hub - Cloud-based bi-directional monitoring and messaging hub
TempoIQ - Cloud-based sensor analytics.
2lemetry - Platform for Internet of things.
Pubnub - Data stream network
ThingWorx - Rapid development and connection of intelligent systems
IFTTT - If this then that
Evrything- Making products smart
NetLytics - Analytics platform to process network data on Spark.
Interesting Readings
Big Data Benchmark - Benchmark of Redshift, Hive, Shark, Impala and Stiger/Tez.
NoSQL Comparison - Cassandra vs MongoDB vs CouchDB vs Redis vs Riak vs HBase vs Couchbase vs Neo4j vs Hypertable vs ElasticSearch vs Accumulo vs VoltDB vs Scalaris comparison.
Monitoring Kafka performance - Guide to monitoring Apache Kafka, including native methods for metrics collection.
Monitoring Hadoop performance - Guide to monitoring Hadoop, with an overview of Hadoop architecture, and native methods for metrics collection.
Monitoring Cassandra performance - Guide to monitoring Cassandra, including native methods for metrics collection.
Interesting Papers
2015 - 2016
2015 - Facebook - One Trillion Edges: Graph Processing at Facebook-Scale.
2013 - 2014
2014 - Stanford - Mining of Massive Datasets.
2013 - AMPLab - Presto: Distributed Machine Learning and Graph Processing with Sparse Matrices.
2013 - AMPLab - MLbase: A Distributed Machine-learning System.
2013 - AMPLab - Shark: SQL and Rich Analytics at Scale.
2013 - AMPLab - GraphX: A Resilient Distributed Graph System on Spark.
2013 - Google - HyperLogLog in Practice: Algorithmic Engineering of a State of The Art Cardinality Estimation Algorithm.
2013 - Microsoft - Scalable Progressive Analytics on Big Data in the Cloud.
2013 - Metamarkets - Druid: A Real-time Analytical Data Store.
2013 - Google - Online, Asynchronous Schema Change in F1.
2013 - Google - F1: A Distributed SQL Database That Scales.
2013 - Google - MillWheel: Fault-Tolerant Stream Processing at Internet Scale.
2013 - Facebook - Scuba: Diving into Data at Facebook.
2013 - Facebook - Unicorn: A System for Searching the Social Graph.
2013 - Facebook - Scaling Memcache at Facebook.
2011 - 2012
2012 - Twitter - The Unified Logging Infrastructure for Data Analytics at Twitter.
2012 - AMPLab - Blink and It’s Done: Interactive Queries on Very Large Data.
2012 - AMPLab - Fast and Interactive Analytics over Hadoop Data with Spark.
2012 - AMPLab - Shark: Fast Data Analysis Using Coarse-grained Distributed Memory.
2012 - Microsoft - Paxos Replicated State Machines as the Basis of a High-Performance Data Store.
2012 - Microsoft - Paxos Made Parallel.
2012 - AMPLab - BlinkDB: Queries with Bounded Errors and Bounded Response Times on Very Large Data.
2012 - Google - Processing a trillion cells per mouse click.
2012 - Google - Spanner: Google’s Globally-Distributed Database.
2011 - AMPLab - Scarlett: Coping with Skewed Popularity Content in MapReduce Clusters.
2011 - AMPLab - Mesos: A Platform for Fine-Grained Resource Sharing in the Data Center.
2011 - Google - Megastore: Providing Scalable, Highly Available Storage for Interactive Services.
2001 - 2010
2010 - Facebook - Finding a needle in Haystack: Facebook’s photo storage.
2010 - AMPLab - Spark: Cluster Computing with Working Sets.
2010 - Google - Pregel: A System for Large-Scale Graph Processing.
2010 - Google - Large-scale Incremental Processing Using Distributed Transactions and Notiﬁcations base of Percolator and Caffeine.
2010 - Google - Dremel: Interactive Analysis of Web-Scale Datasets.
2010 - Yahoo - S4: Distributed Stream Computing Platform.
2009 - HadoopDB: An Architectural Hybrid of MapReduce and DBMS Technologies for Analytical Workloads.
2008 - AMPLab - Chukwa: A large-scale monitoring system.
2007 - Amazon - Dynamo: Amazon’s Highly Available Key-value Store.
2006 - Google - The Chubby lock service for loosely-coupled distributed systems.
2006 - Google - Bigtable: A Distributed Storage System for Structured Data.
2004 - Google - MapReduce: Simplied Data Processing on Large Clusters.
2003 - Google - The Google File System.
Videos
Spark in Motion - Spark in Motion teaches you how to use Spark for batch and streaming data analytics.
Machine Learning, Data Science and Deep Learning with Python - LiveVideo tutorial that covers machine learning, Tensorflow, artificial intelligence, and neural networks.
Books
Streaming
Data Science at Scale with Python and Dask - Data Science at Scale with Python and Dask teaches you how to build distributed data projects that can handle huge amounts of data.
Streaming Data - Streaming Data introduces the concepts and requirements of streaming and real-time data systems.
Storm Applied - Storm Applied is a practical guide to using Apache Storm for the real-world tasks associated with processing and analyzing real-time data streams.
Fundamentals of Stream Processing: Application Design, Systems, and Analytics - This comprehensive, hands-on guide combining the fundamental building blocks and emerging research in stream processing is ideal for application designers, system builders, analytic developers, as well as students and researchers in the field.
Stream Data Processing: A Quality of Service Perspective - Presents a new paradigm suitable for stream and complex event processing.
Unified Log Processing - Unified Log Processing is a practical guide to implementing a unified log of event streams (Kafka or Kinesis) in your business
Kafka Streams in Action - Kafka Streams in Action teaches you everything you need to know to implement stream processing on data flowing into your Kafka platform, allowing you to focus on getting more from your data without sacrificing time or effort.
Big Data - Big Data teaches you to build big data systems using an architecture that takes advantage of clustered hardware along with new tools designed specifically to capture and analyze web-scale data.
Spark in Action & Spark in Action 2nd Ed. - Spark in Action teaches you the theory and skills you need to effectively handle batch and streaming data using Spark. Fully updated for Spark 2.0.
Kafka in Action - Kafka in Action is a fast-paced introduction to every aspect of working with Kafka you need to really reap its benefits.
Fusion in Action - Fusion in Action teaches you to build a full-featured data analytics pipeline, including document and data search and distributed data clustering.
Reactive Data Handling - Reactive Data Handling is a collection of five hand-picked chapters, selected by Manuel Bernhardt, that introduce you to building reactive applications capable of handling real-time processing with large data loads--free eBook!
Distributed systems
Distributed Systems for fun and profit – Theory of distributed systems. Include parts about time and ordering, replication and impossibility results.
Graph Based approach
Graph-Powered Machine Learning - Alessandro Negro. Combine graph theory and models to improve machine learning projects
Data Visualization
The beauty of data visualization
Designing Data Visualizations with Noah Iliinsky
Hans Rosling's 200 Countries, 200 Years, 4 Minutes
Ice Bucket Challenge Data Visualization
Other Awesome Lists
Other awesome lists awesome-awesomeness.
Even more lists awesome.
Another list? list.
WTF! awesome-awesome-awesome.
Analytics awesome-analytics.
Public Datasets awesome-public-datasets.
Graph Classification awesome-graph-classification.
Network Embedding awesome-network-embedding.
Community Detection awesome-community-detection.
Decision Tree Papers awesome-decision-tree-papers.
Fraud Detection Papers awesome-fraud-detection-papers.
Gradient Boosting Papers awesome-gradient-boosting-papers.
Kafka awesome-kafka.
