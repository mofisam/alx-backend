Redis Data Integration
This is the first General Availability version of Redis Data Integration (RDI).

RDI's purpose is to help Redis customers sync Redis Enterprise with live data from their slow disk based databases in order to:

Meet the required speed and scale of read queries and provide an excellent and predictable user experience.
Save resources and time when building pipelines and coding data transformations.
Reduce the total cost of ownership by saving money on expensive database read replicas.
RDI currently supports two scenarios:

Ingest scenario: RDI mirrors the application's primary database to Redis using a change data capture (CDC) tool. RDI transforms the database model and types to a Redis model and types. This scenario is useful when the application database is not performant and scalable enough to serve the read queries. RDI helps you offload all read queries to Redis.
