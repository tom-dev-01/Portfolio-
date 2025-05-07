Below is a tailored README section for your Contact Registry Web App & APIs project, updated to reflect the new requirement of using JavaScript instead of Java. The content aligns with the structure you requested, incorporates the project requirements, and is designed to showcase your skills as a fullstack developer.
Project: Contact Registry Web App & APIs
Project Description
The Contact Registry Web App is a fullstack JavaScript-based application designed to catalog and manage contact information for individuals. It enables users to perform CRUD (Create, Read, Update, Delete) operations on contact details through an intuitive interface, provides an admin dashboard with demographic statistics, and offers a printable report feature filtered by county. The application addresses the need for efficient contact data management and analysis, delivering value through organized data storage, insightful visualizations, and exportable reports.
Features
Contact Management: Perform CRUD operations to add, view, update, and delete contact details (Full Names, Phone Number, Email Address, ID Number, Date of Birth, Gender, County of Residence).
Admin Dashboard: Displays graphical charts of contacts by Gender and County of Residence, plus a table listing the 5 most recently added contacts.
Printable Reports: Generate downloadable PDF reports of contact details, with filtering by County of Residence.
Responsive Design: Ensures a seamless experience on both desktop and mobile devices.
User Authentication: Secure login for admin and regular users to access specific functionalities.
Technologies Used
Frontend: React, Tailwind CSS
Backend: Node.js, Express
Database: MongoDB
Other:
JWT for authentication
Axios for API calls
Chart.js for dashboard visualizations
jsPDF or pdfmake for generating printable PDF reports
Mongoose for MongoDB ORM
Installation Instructions
Clone the Repository:
bash
git clone https://github.com/yourusername/contact-registry-app.git
Navigate to the Project Directory:
bash
cd contact-registry-app
Install Dependencies:
For the backend:
bash
cd server
npm install
For the frontend:
bash
cd ../client
npm install
Set Up the Database:
Install MongoDB and ensure it's running locally or use a cloud service like MongoDB Atlas.
Update the database connection string in server/.env.
Set Up Environment Variables:
Create a .env file in the server directory with:
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
Optionally, create a .env file in the client directory for frontend configuration:
REACT_APP_API_URL=http://localhost:5000/api
Run the Application:
Start the backend:
bash
cd server
npm run dev
Start the frontend:
bash
cd client
npm start
Access the App:
Open http://localhost:3000 in your browser.
