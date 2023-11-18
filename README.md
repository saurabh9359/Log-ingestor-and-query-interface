# Log Ingestor System

This system is designed to ingest logs over HTTP and provide a querying interface using Elasticsearch.

## Prerequisites

- Java JDK installed
- Elasticsearch installed and running on port 9200

## Running the Log Ingestor

1. Compile the LogIngestor.java file.
2. Run the compiled Java file. The ingestor will start on port 3000.
3. Send POST requests with log data to http://localhost:3000/ingest.

## Running the Log Query Interface

1. Compile the LogQuery.java file.
2. Run the compiled Java file to query the Elasticsearch logs.

## Usage

- Ingest logs by sending POST requests with log data to /ingest endpoint.
- Query logs using Elasticsearch queries in the LogQuery file.

