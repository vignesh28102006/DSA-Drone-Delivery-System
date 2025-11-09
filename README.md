# 🚁 DSA Drone Delivery System

A **Java-based Drone Delivery System** project built to demonstrate **Data Structures and Algorithms** concepts through a real-world simulation.  
This project models drone delivery routes, weather conditions, charging stations, and no-fly zones — all managed efficiently using advanced algorithmic logic.

---

## 🧠 Overview

The **DSA Drone Delivery System** simulates how delivery drones can optimize their routes and resources while considering real-world constraints like:
- Weather fluctuations
- No-fly zones
- Charging stations
- Delivery points and warehouses

The project was developed as part of coursework at **Amrita Vishwa Vidyapeetham**, showcasing how DSA principles power practical systems.

---

## ✨ Key Features

✅ **Route Optimization** – Uses graph algorithms to calculate efficient paths  
✅ **Segment Tree Service** – Handles range queries and updates efficiently  
✅ **Weather Handling** – Simulates weather conditions and their effect on drone movement  
✅ **No-Fly Zone Detection** – Prevents path conflicts dynamically  
✅ **Modular Java Architecture** – Clean separation using `models`, `services`, and `utils` packages  

---

## 🗂️ Project Structure

src/
├── main/
│ ├── Main.java # Entry point for execution
│ ├── testcases.java # Contains test cases
│
├── models/
│ ├── Drone.java # Represents drone details
│ ├── Warehouse.java # Warehouse information
│ ├── DeliveryPoint.java # Delivery location model
│ ├── ChargingStation.java # Charging station data
│ ├── NoFlyZone.java # Restricted airspace model
│ ├── WeatherCondition.java # Simulates environmental factors
│
├── services/
│ ├── DroneService.java # Drone management logic
│ ├── RouteService.java # Graph-based route optimization
│ ├── SegmentTreeService.java # Range-based computation service
│ ├── WeatherService.java # Handles weather adjustments
│ ├── DatabaseService.java # Manages data storage
│
└── utils/
├── GraphUtils.java # Graph utilities and helper methods

yaml
Copy code

---

## 🧰 Tech Stack

| Component | Details |
|------------|----------|
| **Language** | Java |
| **IDE** | VS Code / IntelliJ IDEA |
| **Concepts Used** | Graphs, Segment Trees, OOP Design, Service-Oriented Architecture |

---

## ⚙️ How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/vignesh28102006/DSA-Drone-Delivery-System.git
   cd DSA-Drone-Delivery-System
Open the project

Open the folder in VS Code, IntelliJ IDEA, or Eclipse.

Run the main file

Navigate to src/main/Main.java

Run the file (right-click → Run Java Program)

Optional: Run test cases

Run src/main/testcases.java to validate algorithm correctness.

🧪 Example Use Cases
Simulate drone delivery between multiple warehouses and destinations.

Test algorithm performance under weather or route restrictions.

Modify graph weights to mimic real-time logistics challenges.

📸 Future Enhancements
GUI dashboard for live drone visualization

Integration with map APIs

Machine learning–based weather forecasting

Multi-drone optimization using concurrent data structures


🪪 License
This project is open-source and intended for educational use.
You are free to use and modify it with attribution.

⭐ Contribute
If you’d like to contribute improvements or new algorithms:

Fork this repository

Create a feature branch

Submit a pull request 🚀
