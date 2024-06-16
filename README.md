# FancodeSdetAssignment
## Project Setup

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Maven
- IntelliJ IDEA or Eclipse IDE

### Steps to Setup and Run the Project
1. **Clone the Repository**:
    ```sh
    git clone <repository-url>
    ```
2. **Navigate to Project Directory**:
    ```sh
    cd FancodeSdetAssignment
    ```
3. **Open Project in IDE**:
    - Open IntelliJ IDEA or Eclipse IDE
    - Import the project as a Maven project

4. **Run Tests**:
    - Open `FanCodeSDETAssignment.java`
    - Right-click and select `Run 'FanCodeSDETAssignment'` (In IntelliJ IDEA)
    - Or use the following Maven command:
    ```sh
    mvn test
    ```

## Project Structure
- `src/main/java`: Contains main Java files
- `src/test/java`: Contains test files
- `pom.xml`: Maven configuration file

## Dependencies
- Selenium WebDriver
- TestNG
- RestAssured

## Solution Overview
This project verifies that users in the FanCode city (determined by latitude and longitude) have more than 50% of their todo tasks completed. It utilizes RestAssured for API testing, TestNG for test execution, and Selenium for any potential UI automation (though not directly used in this assignment).
