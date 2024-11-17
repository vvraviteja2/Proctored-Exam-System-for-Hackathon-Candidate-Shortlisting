# Proctored-Exam-System-for-Hackathon-Candidate-Shortlisting
Overview:-
The Proctored Exam System is a lightweight web-based platform designed to securely and fairly evaluate candidates for hackathons. Built entirely with HTML, CSS, and JavaScript, this system allows candidates to take exams remotely while ensuring integrity through webcam monitoring and activity tracking.

This system can be used by hackathon organizers to remotely assess candidates from anywhere in the world. It is designed to be simple yet effective, ensuring a smooth experience for both participants and organizers.

Features:-
Secure Login Page for candidates to access the exam.
Instructions Page to guide candidates before starting the exam.
Quiz Interface to present questions and allow for timed responses.
Real-Time Webcam Monitoring using the browser’s camera to ensure fair play.
Results Page to display scores and track candidate progress.
Web-Based: No installation required—just run in a browser.
Software Requirements:-
1. Operating System
Windows: Windows 7 or later
macOS: Mojave or later
Linux: Ubuntu 16.04 or later
2. Web Browser
Google Chrome (latest version)
Mozilla Firefox (latest version)
Microsoft Edge (latest version)
3. Web Technologies
HTML5: For building the page structure.
CSS3: For styling the page and making the interface responsive.
JavaScript: For dynamic interactions, handling the proctoring mechanism, and managing the exam functionality.
4. Libraries & APIs
Media Devices API: To access the webcam and monitor candidates during the exam.
How It Works
Login Page: Candidates log in using a simple authentication process. This page could be extended later to include real authentication (like OAuth), but for now, it's just a placeholder.

Instructions Page:- Once logged in, candidates are shown instructions about the exam, including the rules of the hackathon and any relevant details about the proctoring process. The page explains how their webcam will be monitored.

The Exam Interface:-

Questions are displayed one at a time in a simple multiple-choice format.
A timer is displayed to show how much time is remaining.
JavaScript handles the question flow, timing, and ensures candidates submit their answers within the time limit.
Webcam Monitoring:

The Media Devices API is used to access the webcam.
Real-time webcam monitoring is handled through JavaScript. The webcam feed is displayed on the candidate’s screen to show they are being monitored.
This webcam data can also be logged for review by organizers (though this project is focused on the front-end functionality).
Results Page: After completing the exam, candidates are shown a results page where they can see their score and feedback on the exam.
