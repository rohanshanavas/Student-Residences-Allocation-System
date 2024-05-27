# Hostel Room Allocation System

## Project Overview

To simplify the overall process of hostel room allocation, we developed this web application which will be beneficial for both students and the hostel administrators. The application ensures a transparent and efficient room allocation process.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python
- **Database:** MongoDB

## Features

### Admin Module

1. **Admin Login:**
   - Hostel administrators can log in using their admin credentials.
   - Upon successful authentication, the user is redirected to the admin page.
   - If credentials are incorrect, an alert message is displayed.

2. **Applications Received:**
   - Admins can view a list of students who have applied for rooms in the hostel.
   - The list displays students' roll numbers, the hostels they have applied for, and their room choices in decreasing priority order.

3. **Hostel Rooms:**
   - Admins can view a list of rooms in the hostel and information about their allocation status.
   - An "Allocate" button is provided to allocate rooms to students based on applications received, prioritizing students with higher CGPAs.

4. **Admin Profile:**
   - Contains basic information about the admin and the hostel they manage.

5. **Log Out:**
   - A button to log out from the admin profile.

### Student Module

1. **Student Registration and Login:**
   - Students can register on the portal and log in using their credentials.

2. **Student Profile:**
   - Displays student information such as name, email, phone number, CGPA, and branch.

3. **Choice Filling:**
   - Allows students to enter their room choices for a particular hostel.
   - Students can add multiple room choices in a comma-separated manner.

4. **Log Out:**
   - A button to log out from the student profile.

## Installation and Setup

### Prerequisites

- Install MongoDB Community Server:
  - Download the installer from [MongoDB Community Server](https://www.mongodb.com/try/download/community) and run the installer.

- Install Node.js:
  - Download the installer from [Node.js](https://nodejs.org/en/download/prebuilt-installer) and run the installer.

### Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/rohanshanavas/Hostel-Room-Allocation-System.git
   cd hostel-room-allocation-system
   ```

2. **Install Frontend Dependencies:**
   ```bash
   cd frontend
   npm install
   ```

3. **Install Backend Dependencies for Python:**
   ```bash
   cd ../backend
   pip install -r requirements.txt
   ```

4. **Set Up and Start the Backend Server:**
   ```bash
   python3 loginreg.py
   ```

5. **Start the Frontend:**
   ```bash
   cd ../frontend
   npm start
   ```
