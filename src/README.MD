# Change log level in a Spring boot application during runtime

~~~
curl -i -X POST -H 'Content-Type: application/json' -d '{"configuredLevel": "DEBUG"}'  http://localhost:8080/actuator/loggers/com.siemens.logging.rest
~~~

https://www.baeldung.com/spring-boot-changing-log-level-at-runtime