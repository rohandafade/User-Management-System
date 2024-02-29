# User-Management-System
This is a simple User Management System implemented in Angular with features for creating, updating, and deleting user information. It includes a basic user interface for managing user data.

## Features
### User Module:
* User-Upsert Component: Create and update user information with validation.
* User-List Component: Display a list of users with edit and delete functionalities.

### Validation:

* Required fields for user creation.
* Email validation for the email field.
* Phone field accepts only 10-digit numbers.

###  Data Management:

* Users can be added, updated, and deleted.
* User data is stored and managed using an in-memory API.

### Styling:

* Basic styling for a visually appealing interface.

##  Getting Started
1. Clone this repository.
2. Install dependencies using npm install.
3. Run the development server using ng serve --open.

## Components
### User-Upsert Component
This component allows users to create or edit user information. It includes a form with fields for First Name, Last Name, Address, Email, and Phone. Validation rules are applied to ensure data accuracy.

### User-List Component
The User-List component displays a grid of all users. It includes columns for Name, Email, Phone, and Actions. Users can edit or delete individual entries from this list.

## Usage
1. Navigate to the User List page to view existing users.
2. Click on "Add User" to create a new user, filling out the required fields.
3. To edit a user, click on the "Edit" button next to the user's information in the list.
4. To delete a user, click on the "Delete" button next to the user's information in the list.

## Technologies Used
* Angular
* Angular Material
* Angular In-Memory Web API
  
## Contributors
* Rohan Dafade
  
## License
This project is licensed under the MIT License - see the LICENSE file for details.
