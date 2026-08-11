# Smart Attendance Management System - Frontend

This repository contains the frontend UI for the Smart Attendance Management System.

## Features
- **Dashboard (`index.html`)**: Real-time stats, attendance history, student count, model status.
- **Live Attendance Camera (`camera.html`)**: Web-cam based real-time face detection and attendance logging.
- **Registration Camera (`register_camera.html`)**: Student registration with guided face sample capture.
- **Database Viewer (`db_view.html`)**: Admin viewer for student records and attendance history.
- **Responsive Styling (`static/style.css`)**: Modern dark-themed glassmorphism design.

## Configuration

To connect this frontend to a separately deployed backend (e.g., Render, Railway, Heroku, or VPS):

Set `window.API_BASE_URL` in your HTML or script:
```javascript
window.API_BASE_URL = "https://your-backend-api.onrender.com";
```
When running locally with Flask, leave `window.API_BASE_URL` blank or unset.

## Deployment Instructions

### Vercel / Netlify / GitHub Pages
Deploy the root of this repository directly as a static website.
- **Framework Preset**: Other / None (Static HTML)
- **Publish Directory**: `./`
