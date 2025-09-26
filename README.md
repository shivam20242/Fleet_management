# Fleet Management Dashboard (Admin + Driver)

**Fleet Management Dashboard** is a fullstack MERN application designed for logistics and transport companies to manage fleets in real-time.  
It provides **admin and driver panels**, integrates with **Google Maps** for live tracking, and streamlines task assignment between factories, drivers, and trucks.  

The system helps admins assign trucks to drivers, while drivers receive notifications, update trip statuses, and mark locations on the map for live monitoring.  

---

## ✨ Features

- 🏭 **Admin Panel** – Assign trucks to drivers and monitor fleet activity  
- 🚚 **Driver Panel** – Drivers receive assigned tasks and mark trip updates  
- 🗺 **Google Maps Integration** – Real-time location tracking and route visualization  
- 🔔 **Task Notifications** – Instant alerts when trucks are assigned  
- 📊 **Dashboard View** – Centralized view of ongoing trips, completed routes, and fleet health  
- 👥 **Role-Based Access** – Separate views for Admin and Driver  

---

## 🛠 Tech Stack

- **Frontend:** React.js + TypeScript  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT (JSON Web Tokens)  
- **Maps & Location:** Google Maps API  
- **Deployment:** Netlify (Frontend), Render/Heroku (Backend)  

---

## 🚀 Getting Started

### ✅ Prerequisites
- [Node.js](https://nodejs.org/) installed  
- [MongoDB](https://www.mongodb.com/) running locally or via MongoDB Atlas  
- [Google Maps API Key](https://developers.google.com/maps/documentation/javascript/get-api-key)  

---

### ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/fleet-management-dashboard.git
   cd fleet-management-dashboard
2.Install dependencies for both frontend & backend:

bash
Copy code
cd client
npm install
cd ../server
npm install
Set up environment variables:
Create a .env file in the server folder and add:

env
Copy code
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
Run the backend server:

bash
Copy code
cd server
npm run dev
Run the frontend app:

bash
Copy code
cd client
npm start
💻 Usage
Admin Side
Log in as Admin

Assign trucks to drivers

Track trips and driver activities in real-time

View all fleets on Google Maps

Driver Side
Log in as Driver

Receive assigned trucks and trips

Update task status from the dashboard

Location is pinned on Google Maps for Admin tracking

📂 Project Structure
bash
Copy code
fleet-management-dashboard/
│── client/         # React frontend
│── server/         # Node.js + Express.js backend
│── models/         # MongoDB schemas (users, trucks, assignments)
│── routes/         # API endpoints
│── controllers/    # Business logic
│── .env            # Environment variables
│── package.json
🔮 Future Enhancements
📍 Geofencing for route alerts

🔔 Push notifications for delays or breakdowns

📊 Analytics dashboard for trip performance

📱 Mobile app for drivers with offline support

🌐 Live Demo & GitHub
Live: Fleet Management Dashboard(https://67a988a85c17bbeeff1a1d67--splendid-dolphin-ec07a7.netlify.app)
