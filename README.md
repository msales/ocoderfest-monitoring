## Installation

1. Build the `docker-compose build`
2. Create the network `docker network create --driver bridge ocoderfest-dev`
3. Start the containers `docker-compose up`
4. Test it out by visiting one of the websites like:
```
http://grafana.ocoderfest.dev:8888
http://influxdb.ocoderfest.dev:8888
```

---

WARNING:
Not ready for production, use for testing purposes only.