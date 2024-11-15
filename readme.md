

# **Note App**

A simple Note App built with a **React.js** frontend and a **Node.js** backend connected to **MongoDB**. The app allows users to create and manage notes efficiently. This project is ideal for understanding the basics of MERN (MongoDB, Express.js, React.js, Node.js) stack development.

---

## **Features**
- Create, view, and manage notes.
- Backend API with MongoDB for data storage.
- Minimal and user-friendly React.js frontend.
- Modular folder structure for clarity.

---

## **Project Structure**

```
note-app/
├── backend/       # Contains the Node.js backend
├── note-app/      # Contains the React.js frontend
└── README.md      # Project documentation
```

---

## **Technologies Used**
- **Frontend**: React.js
- **Backend**: Node.js with Express.js
- **Database**: MongoDB

---

## **Setup Instructions**

### **Prerequisites**
Ensure you have the following installed:
- **Node.js**: [Download Node.js](https://nodejs.org)
- **MongoDB**: [Install MongoDB](https://www.mongodb.com/try/download/community)
- **npm** or **yarn**: Comes with Node.js installation.

---

### **1. Clone the Repository**
```bash
git clone <repository-url>
cd note-app
```

---

### **2. Backend Setup**
1. Navigate to the `backend` folder:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up MongoDB connection:  
   - Create a `.env` file in the `backend` folder:
     ```
     MONGO_URI=mongodb://localhost:27017/notes
     PORT=5000
     ```
4. Start the server:
   ```bash
   npm start
   ```
   The backend will run at `http://localhost:5000`.

---

### **3. Frontend Setup**
1. Navigate to the `note-app` folder:
   ```bash
   cd ../note-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the React development server:
   ```bash
   npm start
   ```
   The app will run at `http://localhost:3000`.

---

## **API Endpoints**
| Method | Endpoint         | Description              |
|--------|------------------|--------------------------|
| GET    | `/api/notes`     | Fetch all notes          |
| POST   | `/api/notes`     | Create a new note        |
| DELETE | `/api/notes/:id` | Delete a note by ID      |

---

## **How to Use**
1. Start both the backend and frontend servers.
2. Open `http://localhost:3000` in your browser.
3. Create, view, and manage your notes seamlessly!

---

## **Future Enhancements**
- Add user authentication.
- Implement edit functionality for notes.
- Add tags or categories to notes.

---

## **Contributing**
Feel free to fork this repository, make your changes, and submit a pull request.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
