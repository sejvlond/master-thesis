# Ondřej Šejvl - Master's thesis

## Suitability analysis of Kubernetes for Seznam.cz

This thesis analyses the suitability of the Kubernetes system in the Seznam.cz’s company environment. The first part of the thesis focuses on the theory and identifies possible problems connected with a switch to this technology. The second part of the thesis describes solving those problems and running the cluster together with other applications.

## Related projects
### Tarsier
> Application fer testing Kubernetes cluster

https://github.com/sejvlond/tarsier

images:
  - https://hub.docker.com/r/sejvlond/tarsier/
  - https://hub.docker.com/r/sejvlond/tarsier_build/

### Kafkafeeder
> Application that transfers logs to Kafka

https://github.com/sejvlond/kafkafeeder

images:
  - https://hub.docker.com/r/sejvlond/kafkafeeder/
  - https://hub.docker.com/r/sejvlond/kafkafeeder_build/

### Go kafkalog
> Apache Kafka log format implementation in Go

https://github.com/sejvlond/go-kafkalog

### Kafkalog Logrus
> Kafkalog hook to logrus

https://github.com/sejvlond/kafkalog-logrus

### Heka
> Some Heka adjustment for greater reliability  

https://github.com/sejvlond/heka

### Heka Kafkalog
> Heka Splitter and Decored plugins that use go-kafkalog

https://github.com/sejvlond/heka-kafkalog

### Kubernetes testing
> Support scripts for testing kubernetes

https://github.com/sejvlond/kubernetes-testing

### Go Ultimate server
> Simple Go server for benchmarking Python and Go in Kubernetes cluster

https://github.com/sejvlond/go-ultimate-server

images:
  - https://hub.docker.com/r/sejvlond/go-ultimate-server/
  - https://hub.docker.com/r/sejvlond/go-ultimate-server_build/

### Python Ultimate server
> Simple Python Tornado server for benchmarking Python and Go in Kubernetes cluster

image: https://hub.docker.com/r/sejvlond/python-ultimate-server/

https://github.com/sejvlond/python-ultimate-server

### cp if not exists and sleep
> image with binary for copy file if not exists yet and then sleep

https://github.com/sejvlond/cp-if-not-exists-and-sleep

image: https://hub.docker.com/r/sejvlond/cp-if-not-exists-and-sleep/
