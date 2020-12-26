## Add this starter dependency into your pom in order to have automatically configured Vibur JDBC connection pool datasource.

**Steps:**
 1. Add dependency into your pom file.
 ```
  <dependency>
      <groupId>com.nidhogg</groupId>
      <artifactId>nidhogg-spring-boot-starter</artifactId>
      <version>1.0-SNAPSHOT</version>
  </dependency>
 ```
 2. Add vibur dependency into your pom file.
 ```
  <dependency>
      <groupId>org.vibur</groupId>
      <artifactId>vibur-dbcp</artifactId>
      <version>25.0</version>
  </dependency>
 ```
 3. Set up vibur datasource using **nidhogg** prefix.
 ```
  nidhogg.datasource.driver-class-name=org.h2.Driver
  nidhogg.datasource.url=jdbc:h2:mem:
  nidhogg.datasource.username=sa
  nidhogg.datasource.password=sa
 ```
