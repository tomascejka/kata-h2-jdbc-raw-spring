# Kata H2 + Spring používající JDBC (prosté použití) 
Hledal jsem nejjednodušší integraci H2 a Spring používající __prosté__ JDBC a připojení k databázi je poolované Apache Commons DBCP (URL4) formou ukázky/příkladu a výsledkem je tento odkaz: [URL2].

Projekt lze snadno spustit:

```sh
mvn clean package && mvn exec:java
```

## Zdroje
+ (URL0) [Connection using JDBC, official](http://h2database.com/html/tutorial.html#connecting_using_jdbc)
+ (URL1) [Data access with JDBC](https://docs.spring.io/spring/docs/current/spring-framework-reference/html/jdbc.html)
+ (URL2) [Spring JDBC Example](http://www.journaldev.com/2593/spring-jdbc-example)
+ (URL3) [Spring + JDBC example](http://www.mkyong.com/spring/maven-spring-jdbc-example/)
+ (URL4) [Apache Commons DBCP](https://commons.apache.org/proper/commons-dbcp/)
