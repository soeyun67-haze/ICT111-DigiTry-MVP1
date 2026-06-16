
# Initial IT Venture Idea Log
**Team:** DigiTry
**Course:** ICT11 – Introduction to Information Technology
**Instructor:** Dr. Herison Surbakti
**Date:** Lab 1

---

## Idea 1: SmartTimetable

### Problem Area
Rangsit University students and lecturers have no unified, real-time source for class schedules, room assignments, and last-minute changes. Schedule information is scattered across PDF documents, LINE group chats, and verbal announcements, making it difficult to track room availability, detect conflicts, or receive timely updates when classes are cancelled or relocated.

### Target Users
Rangsit University students, lecturers, and administrative staff.

### Current Alternative
Students rely on printed or PDF timetables distributed at the start of the semester, LINE group chats for informal updates, and word-of-mouth from classmates when rooms or times change. There is no centralized system that reflects real-time changes.

### Proposed IT Solution
A web-based timetable platform where students can view their personalized weekly schedule, search room availability, and receive instant notifications via LINE Notify when a class is cancelled, moved, or rescheduled. Lecturers and staff manage entries through a simple admin dashboard.

### Possible Technology
- Web application (React or plain HTML/CSS frontend)
- Cloud-based system (Firebase or Railway for hosting and real-time database)
- Admin dashboard for schedule management
- LINE Notify API for push notifications
- MySQL or Firestore for data storage
- AI-assisted conflict detection (optional enhancement)

### Why This is Suitable
The project addresses a real, daily problem experienced by every student on campus, making validation and user testing straightforward. The core MVP — a schedule viewer with a basic admin panel — can be built within the first half of the semester using web technologies familiar to the team. Features such as LINE notifications and conflict detection can be added incrementally across labs. The team has direct access to target users and can collect survey data and feedback continuously throughout the project.

---

## Idea 2: MindRSU – Student Mental Wellness Check-in

### Problem Area
University students face significant academic pressure, stress, and emotional difficulties throughout the semester, yet many do not seek help due to stigma, lack of awareness of available support, or not knowing how to start the conversation. Mental health issues often go unaddressed until they become serious.

### Target Users
Rangsit University students, and secondarily, university counselors and student welfare staff.

### Current Alternative
Students who seek help must visit the university counseling center in person, which many find intimidating. There is no low-barrier digital channel for students to express how they are feeling, track their emotional wellbeing over time, or get pointed toward the right support resource anonymously.

### Proposed IT Solution
A web-based platform where students can complete a short daily or weekly anonymous mood check-in, view a personal wellbeing trend over time, and access curated self-help resources and RSU counseling contacts. If a check-in indicates significant distress, the system gently surfaces relevant support options. Counselors can view aggregated (non-identifying) mood data across the student body to identify high-stress periods such as exam weeks.

### Possible Technology
- Web application with anonymous session or optional login
- Cloud-based database for mood entry storage (Firebase or Railway)
- AI-assisted sentiment suggestion or resource recommendation based on check-in responses
- Dashboard for counselors to view anonymized trend data
- Mobile-responsive design for quick daily check-ins on a phone

### Why This is Suitable
The core check-in and trend visualization features are technically straightforward, requiring only a form, a database, and a simple chart — all achievable early in the semester. The topic is highly relevant to the student user base and easy to validate through surveys. Anonymity in the MVP removes complex authentication requirements, simplifying the initial build. The project also has social impact value, which strengthens the venture narrative for later pitch labs.

---

## Idea 3: RSU EventHub – Campus Event Discovery Platform

### Problem Area
Student clubs, faculties, and campus units at Rangsit University organize many events throughout the semester, but promotion is fragmented across Facebook pages, Instagram accounts, and LINE groups. Students miss events they would have attended simply because they never heard about them.

### Target Users
Rangsit University students are interested in extracurricular activities, and student clubs or faculty units that organize events.

### Current Alternative
Event organizers post individually on their own social media accounts or LINE groups. Students must follow multiple accounts and groups to stay informed. There is no single place to discover all campus events filtered by faculty, category, or date.

### Proposed IT Solution
A web-based event discovery platform where clubs and faculty units can post events with date, location, description, and a cover image. Students can browse upcoming events, filter by category or faculty, and RSVP. Organizers can see attendance interest and send reminders to registered attendees.

### Possible Technology
- Web application (frontend) with an admin posting interface
- Cloud-based hosting and database (Firebase or Railway)
- LINE Notify or email for event reminders to RSVP'd attendees
- Mobile-responsive design
- Optional: AI-assisted event recommendations based on past attendance or interests

### Why This is Suitable
Event management platforms have well-understood requirements and clear user roles (organizer and attendee), making system design and testing straightforward. The MVP — event listing, filtering, and RSVP — can be completed early in the semester, leaving room for enhancements such as notifications and recommendation features in later labs. The team has direct access to both student attendees and club organizers for user research and prototype testing.
