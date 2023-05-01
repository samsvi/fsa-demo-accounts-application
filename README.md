# PosAm FullStack Academy Demo app

## accounts-application (Backend + API)

Simple Java demo app to simulate backend and API

### Build with:
- SpringBoot 3.0.6
- Java JDK 17


### How to use

Build with maven
```
$ mvn clean install -U 
```

Run
```
java -jar accounts-application-0.0.1-SNAPSHOT.jar
```

Run with config
```
java -jar  accounts-application-0.0.1-SNAPSHOT.jar --spring.config.location=../config/application.yml
```

Show account with specific ID
```
@RequestMapping("/accounts/{id}")
```

Show all accounts
```
@RequestMapping("/accounts")
```

### Copyrights
(C) Stefan Monko (monkos@posam.sk)