# csv-validator-docker

csv-validator-docker provides a Docker build for the [csv-validator](http://digital-preservation.github.io/csv-validator/) tool provided by The National Archives of the UK.

The University of Maryland Libraries has forked this repository from [blastrain/csv-validator](https://github.com/blastrain/csv-validator) in order to deploy the Docker container with a tagged version, rather than just 'latest' as provided at [https://hub.docker.com/r/knocknote/csv-validator/tags](https://hub.docker.com/r/knocknote/csv-validator/tags).

## Building the Docker Image

To build the Docker image named "csv-validator":

```bash
> docker build -t csv-validator .
```

To run the freshly built Docker container:

```bash
> docker run -it --rm csv-validator validate --help
```

## License

See the [LICENSE](LICENSE.txt) file for license rights and limitations.
