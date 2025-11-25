In this project I created a fully responsive registration page using Bootstrap 5, combining a form, table, image section, buttons, and a navigation bar into a single layout.
I used a centered container with a Bootstrap grid and a col-md-8 column to keep the main content at a readable width on larger screens while still allowing it to scale down nicely on smaller devices.
The overall page has a light background, which helps the content cards and dark navbar stand out visually.

The registration form is built using Bootstrap’s form components and grid system.
The first and last name fields are placed side by side using two col-md-6 columns, while the rest of the inputs span the full width of the form.
The form includes fields for first name, last name, email, password, and a checkbox for agreeing to the terms and conditions.
All of the fields are marked as required, and I added a small inline JavaScript handler that works with Bootstrap’s validation classes so the form can’t be submitted if any of the required fields are empty or invalid.
When the user tries to submit, the form shows validation feedback using Bootstrap’s built-in invalid messages.

Below the form, I created a simulated data table inside another Bootstrap card to display sample user submissions.
The table uses Bootstrap’s table, table-striped, and table-hover classes to make the rows easier to read and to give a subtle hover effect when the mouse moves over a row.
The table is wrapped in a table-responsive div so it can scroll horizontally on smaller screens instead of breaking the layout.
I hard-coded three example users — Ben Johnson, Caleb Williams, and DJ Moore — to demonstrate how real data would appear in the table while keeping the layout consistent with the form above it.

The image section is placed after the table and uses a container-fluid with centered content to stretch the section across the page while still aligning visually with the main column.
Inside this section, I used placeholder images from an external source.
The main image uses the img-fluid class so it scales with the width of the page, and the second image uses both img-fluid and rounded-circle to give it a circular, avatar-style look.
This section also includes two buttons: one primary button that is always visible on all screen sizes, and a secondary button that is hidden on smaller devices using the d-none d-md-inline-block responsive utility classes so it only appears on medium and larger screens.

At the top of the page, I built a responsive navigation bar using Bootstrap’s navbar component.
The navbar uses a dark theme with navbar-dark bg-dark to contrast against the light background of the page.
It includes three links — Home, About, and Contact — arranged horizontally on larger screens.
On smaller screens, the navbar collapses into a hamburger menu that can be toggled open and closed using Bootstrap’s built-in JavaScript behavior.
Throughout the page, I relied on Bootstrap’s grid system, utility classes, and responsive features, along with a custom CSS file, to make sure the layout adapts smoothly across different screen sizes while remaining clean and easy to read.
