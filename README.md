# RentApply - Rental Application Portal

RentApply is a web-based application that simplifies the process of applying for property rentals. Users can fill out and submit rental application forms, and admins can manage and review applications efficiently.

## Features

- User-friendly interface for applicants to fill out rental application forms.
- Admin panel to manage and review submitted applications.
- Validation to ensure accurate and complete information.
- Responsive design for seamless use on various devices.

## Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Additional Libraries: Nodemailer, Multer, Mongoose

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/RentApply.git
Navigate to the project directory:

bash
Copy code
cd RentApply
Install dependencies:

bash
Copy code
npm install
Set up your environment variables in a .env file:

makefile
Copy code
PORT=3000
MONGO_URI=your-mongodb-uri
EMAIL_HOST=your-email-host
EMAIL_PORT=your-email-port
EMAIL_USER=your-email-user
EMAIL_PASS=your-email-password
Start the server:

bash
Copy code
npm start
Open your browser and navigate to http://localhost:3000.

Usage
For Applicants
Visit the homepage.
Fill out the rental application form with the required details.
Submit the form to apply for a rental property.
For Admins
Access the admin panel.
View and manage submitted applications.
Update the status of applications as necessary.
File Structure
java
Copy code
RentApply/
├── controllers/
│   └── formController.js
├── models/
│   └── Application.js
├── routes/
│   └── formRoutes.js
├── public/
│   ├── css/
│   └── js/
├── views/
│   └── forms/
│       └── index.ejs
├── app.js
├── package.json
└── README.md
Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are reviewed and approved by the maintainers.

License
This project is licensed under the MIT License.

Developed by Rahul Gawade
