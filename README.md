# Friends Travel Tracker

![Screenshot (29)](https://github.com/user-attachments/assets/63b84fc7-f7ba-43b3-9e3d-ede3b282b03c)
![Screenshot (30)](https://github.com/user-attachments/assets/8e201fee-d27f-4e7c-9402-a013b87f5cf6)


A web application designed to track and manage countries visited by friends. Built with Node.js, Express, EJS, and PostgreSQL for robust data management and dynamic rendering.

## Project Timeline
**July 2024 - August 2024**

## Features

- **User Profiles:** Personalized user profiles with dynamic rendering of visited countries using EJS templates.
- **RESTful Routes:** Seamlessly interact with the app by adding users, managing countries, and switching profiles.
- **Data Management:** Integrated PostgreSQL for efficient and reliable data handling.
- **Responsive Design:** Enhanced user experience with responsive layouts and custom map styling using JavaScript and CSS.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/friends-travel-tracker.git
   cd friends-travel-tracker
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up PostgreSQL:
   - Ensure a PostgreSQL server is running.
   - Create a database named `travel_tracker`.
   - Update database credentials in the code.

4. Start the server:
   ```bash
   node app.js
   ```

5. Access the application at [http://localhost:3000](http://localhost:3000).

## Application Workflow

1. **User Management:**
   - Create new users with names and preferred colors.
   - Switch between user profiles to track individual visited countries.

2. **Country Tracking:**
   - Add countries to a user's visited list by entering the country name.
   - View dynamically updated country lists for each user.

3. **Dynamic Rendering:**
   - Use EJS templates to render user-specific data, such as visited countries and profile colors.

## Technologies Used

- **Backend:** Node.js, Express
- **Frontend:** EJS, JavaScript, CSS
- **Database:** PostgreSQL

## License

This project is licensed under the MIT License. See the LICENSE file for details.
