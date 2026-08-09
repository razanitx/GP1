# AFAQ

### Personalized Event Discovery and Organization Platform

AFAQ is a web-based platform designed to simplify and personalize event discovery in Riyadh, Saudi Arabia. The platform brings event information into one place and helps users discover, organize, and plan events based on their interests and schedules.

---

## Overview

AFAQ addresses the challenge of fragmented event information across websites, applications, and social media platforms.

The platform provides a centralized and user-friendly environment where residents and visitors in Riyadh can browse events, search and filter available activities, view detailed event information, save favorites, organize events through a personal calendar, and receive personalized recommendations.

AFAQ also integrates a Gemini-powered chatbot to support users through natural language interaction and assist with event discovery.

---

## Problem Statement

Event information in Riyadh is distributed across multiple digital platforms, making it difficult for users to efficiently discover events that match their interests and schedules.

Users may need to search through different sources, compare information manually, and save event details separately. This can lead to wasted time, confusion, missed opportunities, and difficulty organizing activities.

AFAQ aims to address this problem by providing a centralized platform for organized, personalized, and efficient event discovery.

---

## Solution

AFAQ provides a unified platform for discovering and organizing Riyadh events.

Users can browse events by category and date, search for specific events, view detailed information, save events to their favorites, organize selected events through a personal calendar, and receive recommendations based on their preferences and interactions.

The platform also includes a Gemini-powered chatbot that assists users with event discovery and guidance through natural language interaction.

---

## Key Features

### Event Discovery
- Browse Riyadh events through organized event cards.
- View detailed event information including descriptions, dates, times, locations, and official links.
- Search events by name or category.
- Filter events by category and date.
- View top-rated events.
- View events ending today.

### Personalization
- Personalized event recommendations.
- Recommendations based on user preferences and interactions.
- Favorites list.
- Personal calendar.
- Recently viewed events.
- Search history.

### User Accounts
- User registration and login.
- Role-based access control for Users and Admins.
- Profile management.
- Secure logout.
- Password reset through email verification.
- Email verification.

### Admin Management
- Admin Dashboard.
- Add events.
- Update event information.
- Delete events.
- Manage and validate event data.

### AI-Powered Assistance
- Gemini-powered chatbot.
- Natural language interaction.
- Event discovery assistance.
- User guidance.
- Preference collection to support personalization.

---

## Recommendation System

AFAQ uses a **Content-Based Recommendation** approach to provide personalized event recommendations.

The recommendation engine analyzes user interaction data such as:

- Search history
- Favorite events
- Ratings
- Selected categories
- User preferences

This information is used to build a user interest profile and identify events that match the user's interests.

The system applies techniques such as **TF-IDF** and **Cosine Similarity** to represent and compare event and user preference information.

---

## System Architecture

AFAQ follows a **Client-Server Architecture**.

The main components include:

- Client/User Interface
- Flask Backend
- MySQL Database
- Recommendation Engine
- Event Data Processing Module
- Gemini API

The backend handles user requests, business logic, authentication, and communication with the database. The database stores event information, user interactions, and preferences.

---

## Event Data Processing

Event information is collected from publicly available online sources.

The data is:

1. Collected from event sources.
2. Cleaned and validated.
3. Standardized.
4. Transformed into structured JSON format.
5. Integrated with the platform's data model and database.

The processed data supports event browsing, filtering, event details, recommendations, and Admin Dashboard management.

---

## Technologies

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python
- Flask

### Database
- MySQL
- SQLAlchemy
- PyMySQL

### Authentication & Email
- Flask-Login
- Flask-Mail
- Werkzeug

### Template Engine
- Jinja2

### Artificial Intelligence
- Gemini 2.5 Flash
- Content-Based Recommendation
- TF-IDF
- Cosine Similarity

### Development & Collaboration
- Visual Studio Code
- GitHub

---

## Database Design

The system uses MySQL as its relational database management system.

The main entities include:

- User
- Event
- Favorite
- Review
- Rating
- CalendarEvent
- SearchHistory
- UserPreference

The database design uses primary and foreign keys to maintain relationships and data integrity.

---

## User Roles

### User

Users can:

- Browse events.
- Search and filter events.
- View event details.
- Add events to favorites.
- Rate and review events.
- Manage their personal calendar.
- View recently visited events.
- Receive personalized recommendations.
- Interact with the chatbot.

### Admin

Admins can:

- Access the Admin Dashboard.
- Add events.
- Update event information.
- Delete events.
- Manage and validate event data.

---

## UX Design

The AFAQ interface follows user-centered design principles focused on:

- Simplicity and clear navigation.
- Consistency in design.
- Visibility of important information.
- Efficient event discovery.
- User-centered personalization.
- Clear content organization.
- Input validation and error handling.

---

## Scope

The current scope of AFAQ focuses on events within **Riyadh, Saudi Arabia**.

The platform supports modern web browsers such as:

- Google Chrome
- Microsoft Edge

The current release supports **English only** and focuses on displaying event information through external official links rather than providing direct booking or online payment.

The project does not include native mobile applications or integration with closed external systems.

---

## My Contributions

<!-- Add your specific contributions here -->

- [Contribution 1]
- [Contribution 2]
- [Contribution 3]

---

## Project Documentation

The complete Graduation Project I report is available in the `docs` folder.

📄 **[View AFAQ Project Documentation](docs/GP1_Group15_AFAQ_Report.pdf)**

---


## Project Status

**Graduation Project I — Product Release 1**

---

## Team
د
- Razan Almutairi
- Rawasi Almutairi
- Numayir Almoqhim
- Layan Murayshid

**Supervisor:** Dr. Entesar Almosallam
