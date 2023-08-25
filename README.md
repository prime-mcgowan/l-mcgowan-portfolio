The Action Committee for Women in Prison

This is a React web application that provides various pages for users to interact with and access information. The application uses React Router for navigation and Redux for state management.

## Features

Navigation: The application includes a navigation bar that allows users to easily switch between different pages.

Protected Routes: Certain routes are protected, meaning they require the user to be logged in to access. If the user is not logged in, they are redirected to the login page.

User Authentication: User authentication is implemented using Redux and a server API. The application fetches user data upon initialization to determine whether the user is logged in.

Pages: The application includes several pages:

- About Page: Provides information about the application and its purpose.

- User Page: A protected route that displays user-specific information and features.

- Info Page: Displays general information.

- Landing Page: The landing page for the application. Redirects to the user page if the user is already logged in.

- Login Page: Allows users to log in. If the user is already logged in, they are redirected to the user page.

- Registration Page: Allows users to register for the application. If the user is already logged in, they are redirected to the     
  user page.

- Get Involved Page: Provides information about how users can get involved in the application's activities.

- Volunteer Form: A protected route that allows users to submit a volunteer form.

  Volunteer Portal Page: A protected route that displays a portal for volunteers, providing access to relevant information.

  Edit Volunteer Profile: A protected route that allows users to edit their volunteer profile.

  Penpal Profiles: A protected route that displays profiles of penpals.

  Writing Tips: A protected route that provides writing tips for volunteers.

  Get Acquainted Page: A page for users to get acquainted with the application's features.

  Get Informed Page: A page that provides information to users about the application.

## Getting Started

1. Clone the repository to your local machine.
2. Install the required dependencies using npm install.
3. Run the application using npm start.

The application should open in your default web browser.

## Dependencies

- React
- React Router
- Redux
