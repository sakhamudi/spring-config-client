# spring-config-client
Spring Cloud Config Client
Specifically for Spring applications, Spring Cloud Config Client lets you:

Bind to the Config Server and initialize Spring Environment with remote property sources.

Encrypt and decrypt property values (symmetric or asymmetric).

@RefreshScope for Spring @Beans that want to be re-initialized when configuration changes.

Use management endpoints:

/env for updating Environment and rebinding @ConfigurationProperties and log levels.

/refresh for refreshing the @RefreshScope beans.

/restart for restarting the Spring context (disabled by default).

/pause and /resume for calling the Lifecycle methods (stop() and start() on the ApplicationContext).

Bootstrap application context: a parent context for the main application that can be trained to do anything (by default, it binds to the Config Server and decrypts property values).
