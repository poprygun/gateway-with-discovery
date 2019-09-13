# Getting Started

## Start Registry Server

```bash
docker run -p 8761:8761 eureka-server
```

## Test curl commands 

```bash
curl -X GET \
  http://localhost:8080/anything \
  -H 'Accept: */*' \
  -H 'Accept-Encoding: gzip, deflate' \
  -H 'Cache-Control: no-cache' \
  -H 'Connection: keep-alive' \
  -H 'Content-Length: 2' \
  -H 'Content-Type: text/plain' \
  -H 'Host: localhost.readbody.org,localhost.readbody.org' \
  -H 'Postman-Token: 4b02b7af-5b0e-4de0-8351-2c76ca68a7ab,7e611134-7acd-4a21-a979-40a8cec04b34' \
  -H 'User-Agent: PostmanRuntime/7.15.2' \
  -H 'cache-control: no-cache' \
  -d hi
```

### Guides
The following guides illustrate how to use some features concretely:

* [Using Spring Cloud Gateway](https://github.com/spring-cloud-samples/spring-cloud-gateway-sample)

