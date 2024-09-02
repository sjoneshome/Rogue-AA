README: Attendance Verification Form

Overview

This HTML file provides a simple web form for attendance verification. Users can enter their first name, last name, date of attendance, and email address. Upon submission, the form sends an email with the provided details using the EmailJS service. The form also automatically sets the current date in the Date of Attendance field based on the America/Los_Angeles time zone.

Features
Responsive Design: The form is styled to be user-friendly and responsive with a clean and modern look.
Date Auto-fill: Automatically sets the current date in the date input field, formatted as YYYY-MM-DD.
Email Integration: Utilizes EmailJS to send the form data to a specified email address.
HTML Structure
Form Fields:

First Name: A text input field for entering the user's first name.
Last Name: A text input field for entering the user's last name.
Date of Attendance: A date input field pre-filled with the current date.
Email Address: An email input field for entering the recipient's email address.
Submit Button: A button to submit the form.

Styling
The form is styled with CSS to:

Center the form on the page.
Use a light grey background for the body and a white background for the form.
Style input fields and the submit button for better user interaction.
JavaScript Functionality
EmailJS Initialization: The EmailJS library is initialized with a public key to enable email sending functionality.
Date Handling:
Uses Moment.js and Moment Timezone to get and format the current date.
Sets the date input field to today's date in YYYY-MM-DD format.
Form Submission:
Prevents the default form submission behavior.
Retrieves and formats the form data.
Sends an email using EmailJS with the provided details.
Dependencies
Moment.js: Used for date manipulation and formatting.
Moment Timezone: Used for handling time zones.
EmailJS: Provides the email sending functionality.
Setup
Include Dependencies: Ensure the following scripts are included in the HTML <head>:

html
Copy code
<script src="https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.29.4/moment.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/moment-timezone/0.5.34/moment-timezone-with-data.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@4/dist/email.min.js"></script>
EmailJS Configuration: Replace the placeholder public key (_7rIdDEfftg8MsaPA) with your actual EmailJS public key.

Service and Template IDs: Ensure you replace "service_f4gd9ow" and "template_r98lczb" with your actual EmailJS service ID and template ID.

Usage
Open the HTML file in a web browser.
Fill out the form fields.
Click the "Submit" button.
An email will be sent with the provided details, and a success or error message will be displayed based on the result.
Troubleshooting
Email Not Sent: Ensure that your EmailJS public key, service ID, and template ID are correctly configured.
Date Not Set: Verify that Moment.js and Moment Timezone scripts are loaded correctly.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For questions or support, please contact sjoneshome@sbcglobal.net.


-------------------------------------------------------------
Helpful Suggestions:

Here's how to enable autofill in Chrome, Edge, and Safari: 

Chrome
Click the three dots in the top right corner, select Settings, then Autofill and passwords. Toggle on the options for addresses, payment methods, and passwords. 

Edge
Go to Settings and more, then Settings, and ensure Save and fill basic info is toggled on. 

Safari
Go to Settings, then Preferences, and select the Autofill tab. Choose which information to use. 
