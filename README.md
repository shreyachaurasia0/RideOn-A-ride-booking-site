# 🚗 RideOn — Ride Booking Platform (Backend)

RideOn is a fullstack website for a ride booking platform that allows users to register, log in, and book rides, while captains can manage their profiles and rides.  
It includes Google Maps API integration for location suggestions, distance/time calculations, and fare estimation.  
Real-time ride updates are powered by **Socket.io** for seamless communication between users and captains.

---

## Features

### User Features
- Register and log in securely with JWT authentication.
- Access and manage user profiles.
- Book rides, view fare estimates, and track ride status in real-time.

### Captain Features
- Register as a captain and add vehicle details.
- Log in/out securely and manage profile.
- Accept, start, and complete rides with live updates.

### Map Services
- Fetch coordinates for a given address.
- Get distance and estimated time between two locations.
- Retrieve address suggestions using Google Maps API.

### Ride Management
- Create, assign, and track rides.
- View fare estimates by vehicle type (auto, car, moto).
- Real-time OTP and ride status tracking using **Socket.io**.

---

## Tech Stack & Skills

| Category | Tools / Skills |
|-----------|----------------|
| **Language & Framework** | Node.js, Express.js |
| **Database** | MongoDB (Mongoose) |
| **Authentication** | JWT (JSON Web Token), bcrypt |
| **Real-time Communication** | Socket.io |
| **API Design** | RESTful APIs |
| **External APIs** | Google Maps API |
| **Environment & Config** | dotenv, cookie-parser |
| **Version Control** | Git & GitHub |
| **Deployment Ready** | Supports cloud deployment (Render, Railway, Vercel backend) |

---

## ⚙️ API Endpoints

### User Routes
| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | `/users/register` | Register a new user |
| POST | `/users/login` | Log in as a user |
| GET | `/users/profile` | Get user profile |
| GET | `/users/logout` | Logout user |

### Captain Routes
| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | `/captains/register` | Register a new captain |
| POST | `/captains/login` | Log in as a captain |
| GET | `/captains/profile` | Get captain profile |
| GET | `/captains/logout` | Logout captain |

### Map Routes
| Method | Endpoint | Description |
|--------|-----------|-------------|
| GET | `/maps/get-coordinates` | Get coordinates for an address |
| GET | `/maps/get-distance-time` | Get distance & duration between two locations |
| GET | `/maps/get-suggestions` | Get autocomplete address suggestions |

### Ride Routes
| Method | Endpoint | Description |
|--------|-----------|-------------|
| POST | `/rides/create` | Create a new ride |
| GET | `/rides/get-fare` | Get fare estimate for a route |

---

##  Getting Started

###  Clone the Repository
```bash
git clone https://github.com/shreyachaurasia0/Rideon-A-ride-booking-site.git

