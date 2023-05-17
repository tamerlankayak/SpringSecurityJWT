# SpringSecurityJWT

Code working.Solved problem in new version.

![Java_programming_language_logo svg](https://user-images.githubusercontent.com/29164777/226428545-6b06f2e2-99e3-40d9-a6d1-090e2ee94a70.png)
![spring-boot-logo](https://user-images.githubusercontent.com/29164777/226428408-b959b38d-1dc5-4bf7-b5ea-9e7c2932de2e.png)


```
# Spring Security Project with JWT

This project demonstrates how to implement authentication and authorization using Spring Security with JSON Web Tokens (JWT) in a Spring Boot 3 application.

## Features

- User registration and login endpoints
- JWT generation and validation
- Secure API endpoints using JWT
- Role-based authorization

## Technologies Used

- Spring Boot 3
- Spring Security
- JSON Web Tokens (JWT)
- Maven

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 11 or higher
- Maven

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/spring-security-jwt.git
   ```

2. Change to the project directory:

   ```bash
   cd spring-security-jwt
   ```

3. Build the application:

   ```bash
   mvn clean install
   ```

### Configuration

1. Open the `application.properties` file located in the `src/main/resources` directory.

2. Modify the database configuration properties according to your setup. For example:

   ```
   spring.datasource.url=jdbc:mysql://localhost:3306/mydatabase
   spring.datasource.username=db_user
   spring.datasource.password=db_password
   ```

3. Save the changes.

### Usage

1. Run the application:

   ```bash
   mvn spring-boot:run
   ```

2. The application will start on `http://localhost:8080`.

3. Use a tool like Postman to interact with the API endpoints.

### API Endpoints

- `POST /api/auth/register`: Register a new user.
- `POST /api/auth/login`: Authenticate a user and generate a JWT.
- `GET /api/protected/resource`: Access a protected resource.

Note: To access the protected resource, include the JWT in the request header using the `Authorization` header with the value `Bearer <JWT>`, where `<JWT>` is the token obtained after successful authentication.

## Contributing

Contributions are welcome! Please follow the steps below to contribute to this project:

1. Fork the repository.
2. Create a new branch: `git checkout -b my-branch-name`.
3. Make your modifications and commit changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin my-branch-name`.
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```

Make sure to update the placeholders such as `your-username` in the clone URL and customize other sections according to your project. Also, remember to include the appropriate license file (e.g., `LICENSE`) in your repository.
