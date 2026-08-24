The full system covers three user roles (Student, Lecturer, and Academic Leader), my portion specifically implements the **Lecturer module**.


The Lecturer module allows a logged-in lecturer to:

- **View and manage their profile** — display and update personal information (name, age, school, email, date of birth)
- **Manage assessments** — create, view, and manage assessment types (Assignment, Quiz, Final Exam) with titles, marks, and weightage, filtered by the lecturer's assigned modules
- **Enter and review student marks** — view student submissions and record grades using a table-based interface
- **Give feedback** — provide written feedback on student assessments


## Requirements

- Java 21 or above
- Apache NetBeans IDE

## How to Run

1. Open NetBeans
2. Go to **File → Open Project** and select the `NewOOP` folder
3. Right-click the project and select **Clean and Build**
4. Run the project — it will open the Login page
5. Log in with a lecturer account to access the Lecturer module


This project uses text files for data persistence. The following files must remain in the project root directory:

- `users.txt` — user accounts and credentials
- `assessments.txt` — assessment records
- `grades.txt` — student grades
- `submissions.txt` — student submissions
- `modules.txt` — module assignments
- `feedback.txt` — feedback records

## Notes

- The project was built using NetBeans GUI designer (Swing), so `.form` files are required alongside `.java` files
- To login, you can go to the txt file 'users.txt' and get a list of usable usernames(second column) and password(third column)
