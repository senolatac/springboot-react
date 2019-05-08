# Product Purchase And User Management System, Spring Boot, React, MySQL, Hibernate, Liquibase

The application structure is as follows.
- **server-product-management** - Microservice implemented using Spring boot. [More info](server-product-management/README.md)
- **client-product-management** - A NodeJs application implemented using React. This consumes services hosted by server side.  [More info](client-product-management/README.md)

### Build

#### 1) Build Server Side
   
```
$ cd server-product-management
$ gradlew bootJar
$ gradlew bootRun
```

#### 2) Build and run client side

```
$ cd client-product-management
$ npm start
```

### Access server side using following URL

```
http://localhost:8080
```

### Access application using following URL

```
http://localhost:3000
```

