# healtCare-management-system
The **Healthcare Management System** is a web application designed to streamline hospital operations, manage patient records, and enhance the overall efficiency of healthcare services. This system provides an **intuitive interface** for doctors, patients, and administrators to handle hospital workflows efficiently.  
## 🚀 Features  

✅ **User Authentication** – Secure login for patients, doctors, and admins.  
✅ **Patient Management** – Store and manage patient records and appointments.  
✅ **Doctor Management** – Maintain doctor profiles and schedules.  
✅ **Admin Dashboard** – Oversee hospital operations with detailed insights.  
✅ **Responsive Design** – Works seamlessly on both desktop and mobile devices.  

## 🏗️ Technologies Used  

### **Frontend:**  
- React.js  
- React Router  
- Tailwind CSS  
- Lucide Icons  
- Axios (for API communication)  

### **Backend:**  
- Node.js  
- Express.js  
- MongoDB  
- Mongoose (ODM for MongoDB)  
- JWT Authentication  
- dotenv (for environment variable management)  

## 📦 Installation & Setup  

### **Prerequisites**  
- **Node.js** (v14 or higher)  
- **MongoDB** (local or cloud instance)  


2️⃣ Install Frontend Dependencies

cd frontend
npm install
3️⃣ Install Backend Dependencies

cd backend
npm install
4️⃣ Configure MongoDB Connection
Update the server.js and createAdmin.js files in the backend directory with your MongoDB connection string:

javascript

// MongoDB connection
mongoose.connect('<your_MongoDB_connection_string>', {
5️⃣ Create an Admin User
Modify the createAdmin.js file in the backend directory to set up the first admin account:

javascript

const admin = new Admin({
  firstName: "John",
  lastName: "Doe",
  email: "admin@example.com",
  password: "securepassword",
  role: "admin"
});
Then, run the following command once to create the admin user:


node createAdmin.js
🚀 Running the Application
Start the Backend Server

cd backend
node server.js
Start the Frontend Application

cd frontend
npm start
Once both servers are running, open your browser and visit:

🔗 http://localhost:3000

📜 Available Scripts
Inside the frontend directory, you can use:

npm start – Runs the app in development mode.
npm test – Launches the test runner.
npm run build – Builds the app for production.
npm run eject – Ejects the configuration files.
🤝 Contributing
Contributions are welcome!
