# Google Drive Clone

A responsive Google Drive-inspired web application built with **React.js** and **Firebase**, created as a hands-on project to understand modern frontend development, Firebase integration, authentication, and cloud-based file management concepts.

## 🚀 Features

* 🔐 Google Authentication using Firebase
* 📁 Google Drive-inspired file management interface
* ☁️ Firebase integration for cloud storage
* 🗂️ Sidebar navigation and file-view layout
* 🔎 Drive-style user interface
* 👤 User profile integration
* 📱 Responsive React-based UI
* ⚡ Component-based frontend architecture

## 🛠️ Tech Stack

| Technology              | Purpose                                |
| ----------------------- | -------------------------------------- |
| React.js                | Frontend UI and component architecture |
| JavaScript              | Application logic                      |
| Firebase Authentication | Google sign-in                         |
| Firebase Storage        | Cloud file storage                     |
| Firebase Firestore      | Data persistence                       |
| Material UI             | UI components and icons                |
| Create React App        | Development and build tooling          |

## 📂 Project Structure

```text
google-drive-clone/
├── public/
├── src/
│   ├── components/
│   │   ├── filesView/
│   │   ├── header/
│   │   ├── sidebar/
│   │   └── sideIcons/
│   ├── media/
│   ├── styles/
│   ├── App.js
│   ├── App.css
│   ├── firebase.js
│   ├── index.js
│   └── index.css
├── .gitignore
├── package.json
└── yarn.lock
```

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/rathiraghav25/google-drive-clone.git
cd google-drive-clone
```

### 2. Install dependencies

Using Yarn:

```bash
yarn install
```

Or using npm:

```bash
npm install
```

### 3. Configure Firebase

Create a Firebase project and enable the services required by the application:

* Google Authentication
* Cloud Firestore
* Firebase Storage

Update the Firebase configuration in:

```text
src/firebase.js
```

For production projects, Firebase configuration and security rules should be configured appropriately for the deployment environment.

### 4. Start the development server

```bash
yarn start
```

Or:

```bash
npm start
```

The application will be available at:

```text
http://localhost:3000
```

## 🧠 What I Learned

This project helped me gain practical experience with:

* Building reusable React components
* Managing application state with React hooks
* Integrating Firebase services into a React application
* Implementing Google authentication
* Working with Firestore and Firebase Storage
* Structuring a React application into reusable components
* Managing dependencies and scripts with npm/Yarn
* Using Git and GitHub for version control

## 📌 Project Status

This project represents a learning implementation of a Google Drive-style application. Further improvements can include:

* File upload and download workflows
* Folder creation and navigation
* File search and filtering
* File deletion and management
* Improved responsive design
* Better Firebase security rules
* Deployment with a production Firebase configuration

## 📚 Credits & Learning Resource

This project was created as a learning implementation based on the Google Drive Clone tutorial/project by **David Rakosi / Clever Programmer**.

Original reference repository:

https://github.com/davidrakosi/google-drive-clone

The project was used as a learning reference while building and understanding the underlying React and Firebase concepts.

## 📄 License

This repository is intended primarily for educational and learning purposes.
