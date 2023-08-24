<h1 align="center">Welcome to Embracing Microservices Design | Spring | SOAP MongoDB API 🤑</h1>
<h3 align="center">emd-spring-mongo-soap-provider💰</h3>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.0.1--SNAPSHOT-blue.svg?cacheSeconds=2592000" />
  <a href="https://raw.githubusercontent.com/wkmaaj/emd-spring-mongo-soap-provider/master/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/wkmaaj" target="_blank">
    <img alt="Twitter: wkmaaj" src="https://img.shields.io/twitter/follow/wkmaaj.svg?style=social" />
  </a>
</p>

> Embracing Microservices Design - Spring - SOAP to MongoDB API

### Commands

To create a MongoDB container using docker and the compose file and initialization script provided in the root level of the repository, run the following command:

```sh
### the -d flag runs the command in detached mode essentially meaning it runs in the background and you get control of that terminal back
docker compose up -d
```

To ssh into a docker container with bash as your shell, run the following command:

```sh
docker exec -it $CONTAINER_NAME bash

### in the case of a MongoDB image, run the following command to get onto the Mongo shell (mongosh), if no username/password then dont add the -u and -p flags
mongosh -u $USERNAME -p $PASSWORD
```

The below snippet lists some commonly used Gradle commands (via the provided Gradle wrapper in the repository) along with a comment of when to use them:

```sh
### retrieves the Gradle wrapper JARs and script files (log level set to DEBUG)
./gradlew wrapper --debug

### run a clean build (set to capture stacktraces when errors are thrown)
./gradlew clean build --stacktrace

### run tests (log level set to INFO)
./gradlew test --info

### run the application using the Spring Boot Gradle plugin
./gradlew bootRun
```

### References

[Spring Boot Gradle Plugin](https://docs.spring.io/spring-boot/docs/current/gradle-plugin/reference/htmlsingle/)
[Spring Boot Gradle Plugin | Baeldung](https://www.baeldung.com/spring-boot-gradle-plugin)

### 🏠 [Homepage](https://github.com/wkmaaj/emd-spring-mongo-soap-provider)

## Author

👤 **wkmaaj@jaradatbros**

- Twitter: [@wkmaaj](https://twitter.com/wkmaaj)
- Github: [@wkmaaj](https://github.com/wkmaaj)

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2023 [wkmaaj@jaradatbros](https://github.com/wkmaaj).<br />
This project is [MIT](https://raw.githubusercontent.com/wkmaaj/emd-spring-mongo-soap-provider/master/LICENSE) licensed.

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
