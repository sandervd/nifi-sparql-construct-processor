# Apache NiFi SPARQL construct processor

A processor that runs a SPARQL CONSTRUCT query on a FlowFile, and hands over the result of the query to downstream processors.

# Build the NAR file (Jar for NiFi)
```
mvn package
```
This will result in a NAR file being written to the 'nifi-extensions' folder. This folder is shared with the NiFi docker container.

# Download the NiFi client
Download the latest LDES NiFi Processor, and put in 'nifi-extensions' folder
e.g. https://github.com/Informatievlaanderen/VSDS-LDESClient-NifiProcessor/packages/1581623

# Run the stack
```
docker-compose up
```

