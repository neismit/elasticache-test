# elasticache-test

**howto run:**

```
mvn package
cd target

java -Duri="redis://localhost:7000" -Dslots=1000,7000 -Doutperoperation=10 -Dorg.slf4j.simpleLogger.defaultLogLevel=error -jar elasticache-test-1.0-SNAPSHOT-jar-with-dependencies.jar
```