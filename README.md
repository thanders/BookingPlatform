# BookingPlatform


This is a Java project that is based on Java 11 and uses Spring-boot. Maven is used as our build tool.

## Dependencies:

### Spring dependencies
#### Compile (default)
spring

spring-boot-starter

spring-boot-starter-actuator

spring-boot-starter-jdbc

spring-boot-starter-security

spring-boot-starter-web

spring-boot-starter-webflux

spring-session-jdbc

#### Runtime (scope)
spring-boot-devtools

h2

#### Test (scope)
spring-boot-starter-test

reactor-test

spring-security-test

**Note about Maven dependency scope**:

**Compile** is the default scope. Compile dependencies are available in all classpaths of a project.

**Runtime** - indicates that the dependency is not required for compilation, but is for execution. It is in the runtime and test classpaths, but not the compile classpath.

**Test** - indicates that the dependency is not required for normal use of the application, and is only available for the test compilation and execution phases. This scope is not transitive.

Source: https://maven.apache.org/guides/introduction/introduction-to-dependency-mechanism.html
