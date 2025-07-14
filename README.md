#Sports Day 53 - Real-time Seating Dashboard
This project is a web-based, real-time dashboard system designed to manage and display student seating for a "Sports Day 53" event. It features a public dashboard to view team capacity and separate admin desks for each team to update seat counts live. The entire system is built using HTML, CSS, and JavaScript, powered by Google's Firebase platform for the backend.

✨ Features
Live Public Dashboard: A central page (dashboard.html) that displays the total number of available seats and the remaining seats for all four teams (Red, Blue, Purple, and Green).

Real-time Updates: The dashboard and admin desks automatically sync with the database, ensuring the displayed numbers are always current without needing a page refresh.

Dedicated Team Desks: Four separate admin pages (teamA.html, teamB.html, etc.) allow staff for each team to increment or decrement the seat count as students register.

Transactional Integrity: Seat updates are handled using Firebase Transactions to prevent data corruption from simultaneous button presses.

Responsive Design: The pages are styled to be functional and readable on various screen sizes, from mobile phones to desktops.

Central Navigation: A user-friendly index.html serves as a landing page to easily navigate to the public dashboard or any of the team desks.

🛠️ Technologies Used
Frontend: HTML5, CSS3, JavaScript

Backend & Hosting:

Firebase Firestore: Used as the real-time NoSQL database to store team seating data.

Firebase Hosting: Hosts all the static HTML, CSS, and JS files.

Fonts: Google Fonts (Kanit, IBM Plex Sans Thai Looped, Nunito).

