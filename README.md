#🏥Smart_Health_Appointment-Patient_Tracker
A Salesforce project to manage patient information, schedule doctor appointments, and streamline clinic operations.

💡 Problem Statement
Hospitals and clinics often manage patient appointments manually or through spreadsheets, which leads to confusion, double bookings, and poor patient tracking. This project builds a centralized Salesforce system to manage appointments efficiently, track patients, and ensure timely updates.

The system allows users to:
Add and manage patient details.
Schedule, reschedule, or cancel appointments.
Assign doctors to patients automatically.
Send reminders and notifications to patients and doctors.
Maintain secure access for different users (Admin, Doctor, Patient).

🎯 Goals

Create custom objects: Patient, Doctor, and Appointment.
Establish relationships between these objects (lookup/master-detail).
Automate appointment creation and reminders using Flows.
Set up Role Hierarchy, Profiles, and Sharing Rules for data security.
Track login sessions and audit changes.

🏗️ Features

Patient Object → Name, Contact Info, Age, Medical History
Doctor Object → Name, Specialization, Availability
Appointment Object → Appointment Date, Time, Status, Related Patient & Doctor
Automation → Record-triggered Flows for appointment confirmation and reminder emails
Reports & Dashboards → Track doctor appointments, daily visits, and patient counts
Security Controls → Roles, Profiles, OWD, and Sharing Rules

🧠 Tools Used

Salesforce Lightning Experience
Salesforce Flow (for automation and email alerts)
Email Templates & Org-Wide Addresses
Reports and Dashboards
AppExchange (for exploring healthcare add-ons)
