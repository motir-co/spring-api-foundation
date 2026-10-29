# spring-api-foundation

A **Motir foundation template** for the **api** role: a **Spring Boot** (4.1,
Spring Web, Gradle, Java 17) service, exactly as `spring init` generates it.
Motir seeds a project's api repository from this template through
"Use this template" (registry key `spring-api-foundation`).

## What this is

A bare floor, on purpose. It holds the scaffold's output and nothing else: no
auth, no persistence, no API design, no infrastructure. Those are built by the
project's own plan, so no project inherits choices nobody planned. Motir's
hosting does not deploy this foundation, so it carries no
`motir.hosting.json`.

Generated with:

```sh
spring init --type=gradle-project --dependencies=web spring-api-foundation
```

## Get started

```sh
./gradlew bootRun
```

The service starts on <http://localhost:8080>. Run the tests with
`./gradlew test`. See the [Spring Boot documentation](https://docs.spring.io/spring-boot/).

## Licence

[MIT](LICENSE)
