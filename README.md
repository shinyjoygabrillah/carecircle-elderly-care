# CareCircle — Elderly Care & Medication Management

CareCircle is a beginner hackathon prototype for a shared elderly-care routine dashboard.

## Run locally
Open `index.html` in a modern web browser. No build step is required.

## Features
- Medication list with add and taken/not-taken status
- Appointment list with add and remove
- Daily overview and simple adherence count
- Care-circle role preview
- Responsive layout, semantic HTML, keyboard focus indicators and live status messages
- Demo data persisted in browser localStorage

## Important prototype limitations
- Uses fictional sample data only. Do not enter real patient information.
- Role selection is a UI preview, not authentication or authorisation.
- localStorage is not secure storage and does not synchronise between users or devices.
- Email reminders are not implemented; notifications are simulated in the interface.
- This prototype does not provide medical advice or determine medication dosage.

## Suggested next steps
For a production system, add a secure backend, verified authentication, role-based access control, encrypted data storage, audit logs, consent management, scheduled notification service, delivery monitoring, accessibility testing with older adults, and appropriate healthcare/privacy compliance review.

## Test checklist
- [ ] Add a medication and refresh the page; confirm it remains.
- [ ] Mark a medication taken and confirm the count updates.
- [ ] Add an appointment and confirm it appears on the overview.
- [ ] Remove an appointment.
- [ ] Switch care-circle preview roles.
- [ ] Test keyboard navigation and a narrow/mobile screen.
