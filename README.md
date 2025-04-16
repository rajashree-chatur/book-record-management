# book-record-management
Django Project Library 

Getting Started
Follow these simple steps to set up and access the Django Admin Panel:


- Open your terminal in Visual Studio Code (VS Code). You can do this by going to the top menu and selecting: View > Terminal

Step 1: Make Migrations
> python manage.py makemigrations
> python manage.py migrate

Step 2: Create Superuser
> python manage.py createsuperuser

(Example: 
Username: rajashree
Email Address: rajashree11@gmail.com
Password: 123)

Step 3: Run the Development Server
> python manage.py runserver

Step 4: Access Django Admin
- Open your browser and go to: http://localhost:8000/admin
- Log in using the superuser credentials.

Step 5: Manage Books
- In the admin dashboard, click on 'brmapp'.
- Click on 'Books'.
- You can now:
  - Add new books
  - Edit existing books
  - Delete books
