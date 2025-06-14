# 🎫 Ticket-Booking-System (Java Console Application)

This is a **Train Ticket Booking System** built using **Java**. It allows users to **sign up, log in, search trains, book seats, fetch bookings, and cancel tickets**. It uses **JSON files** for local data storage and simulates a real-world ticket booking flow.

---

## ✅ Features

- 🔐 **User Authentication**
  - Sign up with secure password hashing
  - Login functionality with credentials check

- 🚆 **Train Search**
  - Search trains by source and destination
  - View train IDs and station schedules

- 🎟️ **Seat Booking**
  - Display available seats in a 2D grid
  - Book a seat by choosing row and column
  - Stores booking as part of the user

- 📄 **Manage Bookings**
  - View all booked tickets
  - Cancel a booking using the ticket ID

- 💾 **Local JSON Storage**
  - `users.json` to store registered users and their bookings
  - `trains.json` to store available train details and seats

---

## 🛠 Tech Stack

- **Java 17+**
- **Jackson (JSON Parsing)**
- **Gradle / IntelliJ IDEA**
- **Command-line Console Interface**
