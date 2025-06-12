# 🧑‍💼 Job Portal

A full-stack Job Portal web application designed to help job seekers find job opportunities and employers to post job listings. Built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js), this project allows for seamless interaction between users and recruiters.

---

## 🔍 Features

### 🧑 Job Seekers:
- Create and manage profiles
- Browse and search job listings
- Apply to jobs directly
- Track application status

### 🧑‍💼 Recruiters:
- Register and post job listings
- Manage job applications
- Filter and shortlist candidates
- View applicant profiles and resumes

### 🛡️ Authentication:
- Secure login and signup for both job seekers and recruiters
- JWT-based session management

---

## ⚙️ Tech Stack

### 🔧 Frontend:
- React.js
- Redux (if used)
- CSS3 / Tailwind CSS
- Axios

### 🔧 Backend:
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT for authentication

---

## 📁 Project Structure

Job-portal/
├── backend/
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ └── server.js
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ └── App.js
└── README.md

yaml
Copy
Edit

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/mohan-1705/Job-portal.git
cd Job-portal
2. Backend Setup
bash
Copy
Edit
cd backend
npm install
npm start
3. Frontend Setup
bash
Copy
Edit
cd frontend
npm install
npm start
Make sure MongoDB is running locally or update the DB URI in your backend .env file.

📌 Future Improvements
Admin panel to manage users and jobs

Email notifications on application/job update

Resume parsing with AI

Advanced filters and recommendations
