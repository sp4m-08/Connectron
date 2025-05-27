# 🚨 4-DOF Disaster Rover Control Panel

A real-time monitoring dashboard built using **ReactJS** to visualize and track vital sensor data from a disaster-response robot. It interfaces with **Firebase Realtime Database** to display live telemetry like gas levels, tremor activity, flame detection, and more.

![Dashboard Screenshot](./assets/dashboard-preview.png)

---

## 🌟 Features

- 🌡️ Live **Temperature** & **Humidity** display
- 💨 Real-time **Gas Level** monitoring
- 🔥 **Flame Detection** indicator
- 🌍 **Tremor Intensity** and **Impact** levels
- 🛰️ Static **GPS Location** coordinates
- 🎥 Camera feed placeholder for live video stream
- 🔔 Notification panel with auto-alerts (based on thresholds)

---

## 🛠️ Tech Stack

- **Frontend**: ReactJS, CSS
- **Realtime Data**: Firebase Realtime Database
- **Notifications**: Firebase Cloud Messaging (FCM) _(scaffolded but not activated - issues appearing on activation)_
- **Live Reload**: Vite Dev Server (default port: `5173`)

---

## 🔧 Setup Instructions

### 1. Clone this Repository

```bash
git clone https://github.com/your-username/4-dof-disaster-rover.git
cd 4-dof-disaster-rover
```
