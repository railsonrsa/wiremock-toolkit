FROM java:alpine

WORKDIR /wiremock

COPY . .

CMD java -jar wiremock-standalone-2.27.0.jar --root-dir data --port=${WIREMOCK_PORT} --verbose
