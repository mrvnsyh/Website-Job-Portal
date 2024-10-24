# MERN Stack Job Portal Application

This project is a full-featured job portal application built using the **MERN Stack** (MongoDB, Express.js, React, Node.js). It provides a seamless experience for both employers (recruiters) and job seekers. With role-based dashboards, recruiters can post jobs, review applications, and accept/reject them, while job seekers can browse jobs and apply. Admins have their own dashboard to manage the entire system.

## Features

### Authentication & Authorization:
- Secure login and registration using **JSON Web Tokens (JWT)**.
- Three roles: **Admin**, **Recruiters**, and **Users**.
- Each user role has access to its own dedicated dashboard to manage and control specific functions:
  - **Admin**: Manages users, recruiters, and overall system control.
  - **Recruiters**: Posts jobs, manages applications, and reviews applicant profiles.
  - **Users**: Browses jobs, applies for jobs, and tracks application statuses.

### Job Management:
- Recruiters can post jobs, view applicants, and accept or reject applications.

### User-Friendly Dashboards:
- Each role has its own dashboard to monitor and control specific functions.

### Real-time Application Status:
- Users can track their job application statuses.

### Form Validation & State Management:
- Using **React Hook Form** for form handling and **React Query** for server-side data synchronization.

### Responsive Design:
- Mobile-friendly and cross-browser compatible UI using **Tailwind CSS** and **Styled Components**.

## Technologies & Tools Used

### Frontend

- **Framework/Library**:
  - React
  - React DOM
- **Build Tool**:
  - Vite
- **Styling**:
  - Tailwind CSS
  - Styled Components
  - PostCSS
  - Autoprefixer
- **State Management & API Handling**:
  - React Query
  - Axios
- **Form Handling**:
  - React Hook Form
- **UI Components & Utilities**:
  - SweetAlert2 (for beautiful alert boxes)
  - Recharts (for data visualization)
  - React Paginate (pagination)
  - React Datepicker
  - Match-sorter (for fuzzy search functionality)
- **Linting & Formatting**:
  - ESLint
  - ESLint plugins for React and React Hooks

### Backend

- **Programming Language**:
  - JavaScript (Node.js)
- **Framework**:
  - Express.js
- **Database**:
  - MongoDB (via Mongoose)
- **Authentication & Security**:
  - JSON Web Tokens (JWT)
  - bcrypt (for password hashing)
  - cookie-parser
- **Utilities**:
  - Day.js (for date manipulation)
  - express-validator (for validation)
  - dotenv (for environment variables)
- **Development Tools**:
  - Nodemon (for automatic server reloads)

## Project Overview


## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/mern-job-portal.git
    ```

2. **Navigate to the backend and frontend directories**:

    ```bash
    cd mern-job-portal
    cd backend    # For backend
    cd frontend   # For frontend
    ```

3. **Install the dependencies for both frontend and backend**:

   **Backend**:
   ```bash
   npm install

3. **Install the dependencies for both frontend and backend**:

   **Frontend**:
   ```bash
   npm install
   
4. **Set up environment variables for backend (Create .env file and add the following in backend/.env)**:

   ```bash
    echo "MONGO_URI=your_mongo_uri" >> backend/.env
    echo "JWT_SECRET=your_jwt_secret" >> backend/.env
   
5. **Run the backend server**:

   ```bash
    cd ../backend
    npm run dev
   
5. **Run the frontend server**:

   ```bash
      cd ../frontend
      npm run dev

