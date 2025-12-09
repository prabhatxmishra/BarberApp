# 💈 Barber Booking App – Flutter x Firebase

A modern barber shop booking application built with **Flutter** and **Firebase**, following **Clean Architecture** and robust **state management** practices.

Customers can discover barbers, browse available time slots, and book appointments seamlessly, while barbers can manage their schedules and bookings in real time.

---

## ✨ Features

### 👤 Authentication & Profiles
- Email/password sign up & login (Firebase Authentication)
- Persistent login with secure session handling
- Separate roles for:
  - **Customers**
  - **Barbers / Shop Owners**
- Profile data stored in Firestore

### 📅 Booking System
- Browse available barbers
- View barber details (name, rating, services, location, price range)
- Select date & available time slot
- Create, update, and cancel bookings
- Prevent double-booking of the same slot

### 💈 Barber / Admin Features
- Manage available time slots
- View upcoming & past appointments
- See booking details (customer, time, services)
- Optionally manage working days & hours

### 🧭 UI / UX
- Clean, responsive Flutter UI
- Dark/Light theme ready (optional)
- Reusable components for forms, lists, and cards
- Error & loading states handled gracefully

### ☁ Backend (Firebase)
- **Firebase Authentication** for user auth
- **Cloud Firestore** for:
  - Users collection
  - Barbers collection
  - Appointments/Bookings collection
- **Firebase Storage** (optional) for profile/barber images

---

## 🏗 Tech Stack

- **Framework:** Flutter (Dart)
- **Architecture:** Clean Architecture
  - Presentation layer (UI + State Management)
  - Domain layer (Use Cases / Entities / Repositories)
  - Data layer (Firebase implementations)
- **State Management:** (choose the one actually used in project)
  - e.g. Riverpod / Bloc / Cubit / Provider
- **Backend:** Firebase (Auth, Firestore, Storage)
- **Other:**
  - Dart `freezed` / `equatable` for models (optional)
  - Dependency injection (e.g. `get_it` or `riverpod` providers)

---
