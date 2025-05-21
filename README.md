A simple web-based application for managing student assessments using Firebase.

🚀 Features
Firebase Authentication – Secure login system (for future role support: teachers, students, administrators)

Cloud Firestore – NoSQL database to store:

student names

points (scores)

class names

assigned grades

Cloud Storage (planned) – For managing documents such as student report cards (not implemented yet)

📝 Functionality
HTML application form for entering student data:

Name

Points

Class

Grade

Add, edit, delete student entries in the oceny Firestore collection

Live filtering by student name and class

Dynamic class dropdown generated from existing entries in the database

Responsive UI using plain HTML/CSS

📚 Technologies Used
Firebase (App, Firestore, Auth)

Vanilla JavaScript (ES Modules)

HTML5

Optional: TypeScript (planned)

✅ Future Improvements
Role-based login (teacher vs. student view)

Export to CSV

Class-level statistics (average grade, total points)

Firebase Hosting deployment
   
