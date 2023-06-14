# student_database
This project is a simple student database management system that allows you to build a database of students and their specific information. It differentiates between full-time and part-time students and enables the user to enter student information, which is then displayed. The system also provides the option to continue adding more students.

Getting Started
To run this project on your local machine, follow these steps:

Clone the repository or download the project files.
Open the project in your preferred Java IDE.
Locate the Main class and execute it.
Prerequisites
Java Development Kit (JDK) installed on your machine.
Java IDE (such as Eclipse, IntelliJ IDEA, or NetBeans) or a text editor for running the project.
Usage
Launch the program.
When prompted, enter 1 to add a full-time student or 2 to add a part-time student.
Follow the on-screen instructions to enter the student's information, such as their name, address, enrollment date, major, and other relevant details.
Once the information is entered, it will be displayed.
Repeat the process to add more students as needed.

Code Overview
The project consists of a Main Java Class, a Sudent abstract class, FullTimeStudent Class, and a PartTimeStudent Class. Here's an overview of the methods and functionality provided by this class:
The main method is the entry point of the program. It sets up an ArrayList to store the student data and prompts the user for the type of student they want to add.
The getFullTimeStudent and getPartTimeStudent methods are responsible for collecting the necessary information for full-time and part-time students, respectively. These methods instantiate the appropriate student class (FullTimeStudent or PartTimeStudent) and retrieve the required details from the user.
Various helper methods, such as name, address, date, major, standing, creditHours, hasMajor, and NumOfCourses, are used to obtain specific information from the user, performing validations where necessary.
The getStudentNumber method generates a unique student ID number.
The student information is stored in arrays, which are then added to the studentData list.
The program loops and allows the user to continue adding students until a specified limit is reached.
The collected student information is displayed after each entry.
Feel free to modify the code and add additional features or validations based on your requirements.

License
This project is licensed under the MIT License.

Acknowledgments
This project was developed by Tai'Lon Jackson.
