# Hospital-Management-System
Hospital Management System in Java with SQL Backend
Hello and welcome to my Hospital Management System project! The aim is to streamline the operations of hospitals by managing patient records, doctor schedules, and appointment bookings more efficiently.

Features
Patient Management: Ability to add new patients to the system, view patients.
Doctor Management: Manage doctor profiles, including tracking their specializations, schedules, and availability.
Appointment Booking: Facilitate the booking of appointments, allowing patients to find and book available slots with their preferred doctors.
Database Integration: Utilizes MySQL for secure and persistent storage of all hospital data, ensuring robustness and reliability.

Technologies Used
Java: Chosen for its strong object-oriented programming capabilities, Java forms the backbone of the backend logic.
MySQL: For our database needs, MySQL was selected for its efficiency, reliability, and compatibility with Java.
JDBC: Java Database Connectivity (JDBC) allows our application to interact with the MySQL database, handling data manipulation and retrieval.
Visual Studio Code: My preferred integrated development environment (IDE), supporting a wide range of Java and database development plugins.

Getting Started:
Clone the Repository:
git clone https://github.com/yourgithubusername/hospital-management-system.git
Set Up the MySQL Database:
Install MySQL and create a database named hospital.
Use the SQL schema provided in db/schema.sql to initialize the database structure.
Configure the Database Connection:
Inside src/main/java/config/, adjust DatabaseConfig.java to match your MySQL credentials.
Launch the Application:
Open the project with Visual Studio Code.
Navigate to src/main/java/HospitalManagementSystem.java and execute the main method to start the application.
