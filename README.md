# msf-jmeter-tests

JMeter Tests for MSF Web Services

## Usage
`msf-ws-data-service-api.jmx` is configured to use the data service API at
`https://localhost:8080`. If the data service API is hosted at the same location
you only need to set the user defined variable `token` for your environment;
otherwise, set the user defined variables appropriate for your data service API
configuration.

## TODO
* Load user defined variables from an external configuration file
* Add tests for the other data service API endpoints
* Configure test so that output can be easily stored and comparisons made across test runs
