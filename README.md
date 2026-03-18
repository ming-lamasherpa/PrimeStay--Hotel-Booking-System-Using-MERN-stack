# PrimeStay – Hotel Booking System 🏨

PrimeStay is a modern **Hotel Booking System** built using **MERN Stack**.  
The project provides a clean and responsive user interface for browsing hotels, searching destinations, and exploring featured rooms.

## Frontend:
Install Client side package:
- **React.js** > npm install/vite
- **Tailwind CSS** > npm install tailwindcss @tailwindcss/vite
  - First Step : vite.config.ts > import tailwindcss from '@tailwindcss/vite'
  - Second Step: vite.config.ts > plugins: [tailwindcss(),],
  - Third Step: index.css > @import "tailwindcss";
- **React Router DOM** > npm install react-router-dom
- **Lucide react** > npm install lucide-react

## Backend:
Install server package:
- server > npm init -y
- server > npm i express dotenv cors mongoose cloudinary multer svix
- Add: "type":"module", in package JSON.
- server > npm install --save-dev nodemon "server": "nodemon server.js",
- server > npm run server

## Express install:
Install Express package:
- server>npm install @clerk/express
- Add clerkMiddleware():
   - import { clerkMiddleware } from '@clerk/express'
   - app.use(clerkMiddleware())

##  Setup for clone:
1. **Clone the repository**
git clone: [https://github.com/ming-lamasherpa/PrimeStay---Hotel-BookingSystem.git]
