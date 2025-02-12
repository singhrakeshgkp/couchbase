# couchbase Table of contents
- [Basic](#basic)
  - [CAP Theorem](#Cap-Theorem)
  - [Use Cases](#use-cases)
  - [Popular NOSQL DBs](#popular-nosql-dbs)
  - [Document](#document)
  - [Installation and Creating Cluster](#installation-and-creating-cluster)
  - [Bucket](#bucket)
 
# Basic
## CAP Theorem
## Use Cases
- User Session ---> Couchbase Ephemeral/redis
- Financial Data --> RDBS such as oracle, sql server ...etc
- Shoping cart ----> Couchbase Ephemeral/Riak
- Recommendation System--> Neo4j
- Product/Item catalog ---> Couchbase/Mongo DB
- Analytics ----> Couchbase Analytics/Cassandra

## Popular NOSQL DBs
- **Key Value Store** --> Couchbase, Mongo DB, Memcached, Redis
- **Document Store** --> Couchbase, MongoDB, DynamoDB
- **Wide Column Store** ---> Cassandra, ScyallaDB
- **Graph** --> Neo4j
## Document
- Is an entry in database, its basically key/value pair.
- Document that contains data as key/value pair is stored in a bucket. Bukcket is a logical structure on a cluster, each bucket has 1024 vBuckets (shards)
- Data is spread evenly across cluster(with rebalance)
### Types of buckets
- Couchbase Bucket --> Works in memory and disk, asynchronous persistent to disk. 20 MB per item value limit
- Memcached Bucket --> In memory only, for backward compatiability, 1 MB limit
- Ephemeral Bucket --> Alternative to couchbase buckets, limit 20 MB, useful if persistent is not required 
## Installation and creating cluster
- Follow instructions given on official website.
## Bucket
- Creating bucket using CLI
- Creating bucket using rest
- Creating bucket from UI
  
