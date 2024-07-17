Step 5: Configure Application Properties
Make sure your application.properties or application.yml includes the database configuration (URL, username, password).

Step 6: Run the Application
Run your Spring Boot application (main method in your main class) and test the endpoints using tools like Postman or cURL:

POST /customers: Add a new customer with JSON body.
GET /customers/{id}: Retrieve customer information by ID.
GET /customers: Retrieve all customers.
PUT /customers/{id}: Update customer information by ID with JSON body.
