# SpendSmart

SpendSmart is a personal finance application built in Java, designed to help users track and optimize their expenses. By providing insights into spending habits, SpendSmart empowers users to make informed financial decisions and save more effectively.

## Features

- **Expense Tracking**: Easily log and categorize your expenses.
- **Budgeting Tools**: Set budgets for different categories and monitor your spending.
- **Insights & Reports**: Visualize your spending habits with informative charts and reports.
- **Notifications**: Receive alerts for upcoming bills and budget limits.
- **User-Friendly Interface**: Intuitive design for seamless navigation.

## Technologies Used

- **Java**: Core programming language
- **Spring Boot**: Backend framework
- **Hibernate**: ORM for database management
- **Thymeleaf**: Templating engine for the frontend
- **MySQL**: Database for storing user data

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/spendsmart.git
   ```

2. Navigate to the project directory:

   ```bash
   cd spendsmart
   ```

3. Import the project into your favorite IDE (e.g., IntelliJ IDEA, Eclipse).

4. Set up the database:
   - Create a MySQL database named `spendsmart`.
   - Update the database connection settings in the `application.properties` file.

5. Build the project:

   ```bash
   ./mvnw clean install
   ```

6. Run the application:

   ```bash
   ./mvnw spring-boot:run
   ```

## Usage

1. Create an account or log in.
2. Begin adding your expenses.
3. Set budgets and review your spending insights.
