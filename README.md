# Job Portal App with MERN Stack

A comprehensive job portal application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This application allows users to browse job listings, apply for jobs, and manage their applications seamlessly.

<h2>🚀 Demo</h2>

[Website](https://jobportalmern.netlify.app)<br />

## Features

- **User Authentication:** Secure authentication using JWT (JSON Web Tokens) for both job seekers and employers.
- **Job Listings:** Browse through a wide range of job listings fetched from MongoDB.
- **Application Management:** Job seekers can manage their job applications, and employers can view and manage received applications.
- **Responsive Design:** Ensures a seamless experience across all devices.

  ## Technologies Used

- **Frontend:** React.js, React Router, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB
- **Authentication:** JWT (JSON Web Tokens), Bcrypt (for password hash)
- **Image Upload:** Cloudinary for storing and managing uploaded images
  
  ## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

- Node.js installed on your machine with latest version or v22.2.0 above
- MongoDB Atlas account (or local MongoDB server)
- Cloudinary account for image storage


### Installation

1. Clone the repo:
   ```sh
   git clone git remote add origin https://github.com/shubhamgadhiya/Job-Portal-MERN.git
   ```
2. Install NPM packages:
   ```sh
   cd Frontend
   cd Backend
   npm install
   cd..
   cd frontend
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file after creating a `config folder` in the backend directory, containing the following variables:
   ```env
   PORT = 
   MONGODB = 
   SECRET_KEY = 
   EMAIL = 
   PASSWORD = 
   CLOUD_NAME = 
   CLOUD_KEY =
   CLOUD_SECRET_KEY =
   ```

   Replace each value with your specific configuration details.

4. Run the application:
   ```sh
   npm start
   ```
5. Open your browser and navigate to `http://localhost:3000` to view the app.
