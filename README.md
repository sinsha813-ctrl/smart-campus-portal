​Nexus University - Smart Campus Portal
​A modern, responsive enterprise administration and student portal built with HTML5, Tailwind CSS, and Vanilla JavaScript. The Smart Campus System integrates IoT telemetry, real-time energy monitoring, smart parking, facility reservations, academic grade tracking, exam scheduling, and student resources into a unified, single-page application dashboard.
​🌟 Key Features & Modules
​1. Secure Authentication & Role Selection
​Role-Based Access Control: Tailored portal views for Students, Faculty Members, and Campus Administrators.
​Enterprise SSO Mock: Simulated secure login with session management.
​2. Live Dashboard & IoT Telemetry
​KPI Metrics: Active campus population tracking, current power draw (MW), parking space availability, and environmental monitoring (Temperature & Air Quality Index).
​Building Telemetry: Real-time HVAC and occupancy status across academic blocks, central libraries, and cafeterias.
​Emergency Broadcasts: Instant modal triggers for campus-wide safety alerts and digital signage sync.
​3. Student Portal & Academic Tools
​Grade Tracking: Semester-wise GPA calculation, course credits, mid-term scores, and letter grade breakdowns.
​Assignment Submissions: Interactive file upload portal for homework and project deliverables with due-date tracking.
​Examination Timetables: Comprehensive exam schedules, course codes, time slots, exam hall allotments, and hall ticket downloads.
​Previous Year Questions (PYQs): Filterable repository of past semester question papers available for PDF download.
​4. Campus Life & Infrastructure
​Program & Event Scheduling: Upcoming academic symposia, hackathons (e.g., NexusHack), and guest lectures with RSVP/registration actions.
​Smart Parking Management: Ultrasonic floor sensor status tracking across multiple campus lots (Lot A, B, C) with live capacity progress bars.
​Energy Analytics: Power consumption breakdown and telemetry across academic halls, student dormitories, and research data centers.
​Facility Booking: Smart room and auditorium reservation system.
​College Information & Directory: Institution history, accreditation metrics, placement success rates, and key department contacts/extensions.
​🛠️ Technology Stack
​Frontend Framework: Tailwind CSS (via CDN) for utility-first responsive styling.
​Icons: FontAwesome 6.4.0.
​Interactivity: Vanilla JavaScript (ES6+) handling dynamic tab switching, real-time clocks, authentication state, and modal triggers.
​Architecture: Client-side single-page application (SPA) designed for easy integration with backend REST/GraphQL APIs and MQTT IoT brokers.
​🚀 Getting Started
​No complex build steps, package managers, or bundlers are required to run the frontend template.
​Download / Clone Repository:
Save the application code as index.html in your local project directory.
​Open in Browser:
Double-click index.html or open it directly in any modern web browser (Chrome, Firefox, Safari, Edge).
​Login:
Use the default login screen (select your role as Student, Faculty, or Admin and enter any credentials) to access the dashboard.
​📈 Scalability & Production Deployment
​To transform this frontend dashboard into a fully functional production-grade Smart Campus platform:
​Backend API (Node.js + Express or Python + FastAPI):
​Implement RESTful endpoints for user authentication, grade records, and assignment submissions.
​Set up an MQTT Broker (e.g., Mosquitto) to ingest live telemetry from IoT microcontrollers (ESP32/Arduino) deployed across campus parking lots and smart buildings.
​Database Layer (PostgreSQL or MongoDB):
​Store user profiles, department directories, exam schedules, and historical energy logs.
​Storage:
​Integrate cloud storage (AWS S3 or Google Cloud Storage) for PDF question papers, syllabus documents, and student assignment submissions.
