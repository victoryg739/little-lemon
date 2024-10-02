### Little Lemon App

Steps to Create and Submit the Project

Step 1: Set Up a Virtual Environment

For Windows, use the command: python -m venv env. For MacOS, use the command: python3 -m venv env.

Step 2: Activate the Environment

For Windows, run: .\env\Scripts\activate. For MacOS, run: source env/bin/activate.

Step 3: Install Django

For Windows, use: pip install django. For MacOS, use: pip3 install django. To verify the Django version, use: python -m django –version.

Step 4: Start a New Django Project

Run the following command to start a new Django project: django-admin startproject project_name .

Step 5: Create a New Django App

For Windows, use: python manage.py startapp app_name. For MacOS, use: python3 manage.py startapp app_name.

Step 6: Run the Development Server

For Windows, run: python manage.py runserver. For MacOS, run: python3 manage.py runserver.

Step 7: Deactivate the Virtual Environment

Once you’re done working, deactivate the environment by typing deactivate.

Project Overview

In this project, you’ll create a website for the Little Lemon restaurant. Visitors should be able to: View the homepage and navigate to the About, Menu, and Book pages. The Menu page will display a list of menu items stored in the database, each with the following information: Name, Price, Description, and Image. Each menu item will link to a dedicated page that displays its detailed information. You’ll use the Django Admin interface to add the menu items, and they should be displayed in alphabetical order on the menu page.

Grading Criteria

Your peers will evaluate your submission based on the following: Does the homepage contain a working menu link? Does the menu page display a list of items in alphabetical order? Are menu items clickable and do they link to a detailed page? Does the menu item page display all relevant information? Is there a footer section on the website?

Example Submissions

Menu Page: Go to the URL http://127.0.0.1:8000/menu/. Menu Item Page: Go to the URL http://127.0.0.1:8000/menu_item/1/. Exporting and Submitting Your Project Step 1: Download Project Files At the top of the lab, click the Lab Files link. Use the checkbox to select all the files for your project, and click the Download button to download them as a .zip file.

Step 2: Extract the .zip File Once the file is downloaded, extract it to your local machine.

Step 3: Locate and Zip the Project Folder Find the folder named littlelemon inside the extracted files. Zip this folder to prepare it for submission.

Step 4: Submit the Project on Coursera Go to the Peer-graded Assignment in the course. Click the My Submission tab, and enter a project title (you can use your coder ID). Upload the littlelemon.zip file. Check the Coursera Honor Code box, and click Preview. Once ready, click Submit.

How to Review a Project

Step 1: Download Peer Submissions Click the Review Assignments button to download the project submissions of two peers.

Step 2: Upload the Project to the Peer Review Sandbox Follow the instructions in the Peer Review Sandbox to upload your peer’s project, run the server, and test their application.

Step 3: Evaluate the Project After running the project in your browser, answer the provided review questions based on the functionality of the app. Provide helpful feedback if any issues are found.
