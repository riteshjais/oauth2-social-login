# OAuth2 Login Integration using Spring Boot


This Spring Boot project showcases the implementation of OAuth2 login functionality, allowing users to authenticate using their GitHub and Google accounts. OAuth2 is a widely used protocol for secure and seamless user authentication with third-party services, making it an essential feature for many modern web applications.

## Key Features

- **GitHub OAuth2 Integration:** Users can log in with their GitHub accounts, providing a secure and convenient way to access your application.

- **Google OAuth2 Integration:** Additionally, users can choose to log in using their Google credentials, expanding the authentication options and increasing user accessibility.

- **Security and Authorization:** The project emphasizes security best practices, ensuring that user data is protected and authorization is appropriately handled.

## Prerequisites
- Java Development Kit (JDK)
- GitHub Developer Account
- Google Developer Account
- Spring Boot

## Technologies Used
- Spring Boot
- Spring Security OAuth2
- GitHub OAuth2
- Google OAuth2
- Maven 

## Usage

1. Clone the repository: https://github.com/riteshjais/oauth2-social-login
2. Configure OAuth2 settings for GitHub and Google: Create OAuth2 applications on GitHub and Google developer platforms.
3. Update application.properties or application.yml with the OAuth2 client credentials and redirect URIs.
4. Build and run the Spring Boot application: ./mvnw spring-boot:run
5. Navigate to http://localhost:8080
6. Use the GitHub or Google login buttons to authenticate.
