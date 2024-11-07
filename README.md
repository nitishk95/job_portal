Job Portal Website
This project is a full-stack job portal application built using React, Node.js, Chakra UI, and MongoDB. The portal facilitates job seekers in finding relevant job listings and allows recruiters to post and manage job openings. It also includes essential features like user authentication, job filtering, and file uploads using Cloudinary for profile photos and resumes.

Features
1. User Features
User Registration and Login: Secure authentication using tokens.
Profile Management: Update personal details and upload profile photos.
Job Search and Filtering: Search jobs by location, job type, and keywords.
Job Application: Apply for job openings and upload a resume.
View Job Details: Detailed view of each job listing.
2. Recruiter Features
Recruiter Registration and Login: Secure access to manage job postings.
Company Management: Add and manage company information.
Job Post Creation: Create and publish job listings with necessary details.
Manage Applications: View, accept, or reject job applications from candidates.
3. Common Features
Responsive Design: Optimized for both desktop and mobile viewing.
Cloudinary Integration: For storing user profile photos and uploaded resumes.
Role-based Access: Different views and permissions for users and recruiters.
Technologies Used
Frontend
React: For building the user interface.
Chakra UI: For styling and UI components.
Axios: For making API requests.
Backend
Node.js: As the runtime environment.
Express.js: For building the RESTful API.
MongoDB & Mongoose: For database and object modeling.
Cloudinary: For handling media upload

Setup Instructions
Prerequisites
Node.js and npm installed.
MongoDB Atlas account and Cloudinary account setup for media handling.

Installation Steps
Clone the repository:
bash
git clone https://github.com/your-username/job-portal.git

Navigate to the project directory:
bash
cd job-portal

Install dependencies:
For the backend:
bash
cd backend
npm install

For the frontend:
bash
cd ../frontend
npm install


Set up environment variables:
Create a .env file in the backend directory and add the following:
env
PORT=8000
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-jwt-secret
CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
CLOUDINARY_API_KEY=your-cloudinary-api-key
CLOUDINARY_API_SECRET=your-cloudinary-api-secret

Start the development server:
Backend:
bash
npm run dev
Frontend:
bash
npm start
