# Job Portal App

This is a web application built using Django, Python, and SQLite, designed to serve as a job portal where users can search for jobs, apply to them, and manage their applications.

## Features

- **Job Listings**: Display available job listings with details such as job title, company, location, and description.
- **Search Functionality**: Allow users to search for jobs based on keywords, location, or category.
- **User Authentication**: Users can sign up, log in, and log out securely.
- **Apply to Jobs**: Registered users can apply to job listings.
- **Application Management**: Users can view and manage their job applications, including status tracking.
- **Admin Panel**: Administrators can manage job listings, user accounts, and applications through an intuitive admin interface.
- **Responsive Design**: The application is designed to be mobile-friendly and responsive across various devices.

## Technologies Used

- **Django**: Python-based web framework for building the backend.
- **SQLite**: Lightweight and easy-to-use relational database management system.
- **HTML/CSS/JavaScript**: Frontend development languages for creating the user interface.
- **Python**: Programming language used for backend development.
- **Git**: Version control system for tracking changes in the codebase.
- **GitHub**: Hosting platform for version-controlled collaboration on code.

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/vikrampate0408/job-portal.git
2. Navigate to directory
   ```bash
     cd job-portal-app
3. Install dependencies:
   ```bash
     pip install -r requirements.txt
4. Apply migrations:
     ```bash
     python manage.py migrate
5. Create a superuser (admin):
   ```bash
     python manage.py createsuperuser
6. Run the development server:
   ```bash
     python manage.py runserver
7. Access the application in your web browser at http://127.0.0.1:8000/.
