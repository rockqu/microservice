# microservice

Netflix Eureka
Service Discovery Server Netflix Eureka allows microservices to register themselves at runtime as they appear in the system landscape.

Netflix Ribbon
Dynamic Routing and Load Balancer Netflix Ribbon can be used by service consumers to lookup services at runtime. Ribbon uses the information available in Eureka to locate appropriate service instances. If more than one instance is found, Ribbon will apply load balancing to spread the requests over the available instances

Netflix Zuul
Zuul is a gateway service that provides dynamic routing. It uses Ribbon to lookup available services and routes the external request to an appropriate service instance.

Hystrix & Hystrix dashboard
Hystrix is a library for the JVM from Netflix that implements patterns for dealing with downstream failure, offers real-time monitoring of connections, and caching and batching mechanisms to make inter-service dependencies more efficient. In combination with hystrix-dashboard and Turbine, this tool can be used to build more resilient systems and provide near-real time data on throughput, latency and fault tolerance.

