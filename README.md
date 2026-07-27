# Resume Builder

Resume Builder is a full-stack web application for creating, editing, previewing, and sharing professional resumes. It includes a React + Vite frontend and a Node.js/Express backend with MongoDB for storing resume and user data. The app supports multiple resume templates, color customization, AI-assisted resume upload, and public resume preview links.

## Features

- Create and manage multiple resumes
- Edit personal info, summary, experience, education, projects, and skills
- Choose from different resume templates
- Customize accent colors and profile image handling
- Upload a PDF resume and extract text for faster import
- Share public resume preview links
- Download the final resume

## Tech Stack

- Frontend: React, Vite, React Router, Redux Toolkit, Tailwind CSS
- Backend: Node.js, Express, MongoDB, Mongoose
- Other tools: Axios, Multer, ImageKit, OpenAI, React Hot Toast

## Project Structure

- `client/` - frontend application
- `server/` - backend API and database logic

## Local Setup

### 1. Clone the repository

```bash
git clone https://github.com/yashsharmaa69/resume-builder.git
cd resume-builder
```

### 2. Install dependencies

```bash
cd client
npm install
cd ../server
npm install
```

### 3. Configure environment variables

Create the required `.env` files for both client and server based on your deployment and local setup.

### 4. Run the development servers

Backend:

```bash
cd server
npm run server
```

Frontend:

```bash
cd client
npm run dev
```

## Deployment

This project can be deployed as a split app:

- Frontend: Vercel, Netlify, or any static hosting platform
- Backend: Render, Railway, or any Node.js hosting platform
- Database: MongoDB Atlas

After deployment, update the frontend API base URL and backend environment variables so both apps can communicate correctly.

## Live Preview

[Live Preview](https://resume-builder-frontend-lx07.onrender.com)

## GitHub Repository

[GitHub repository link](https://github.com/yashsharmaa69/resume-builder.git)

## Notes

Make sure the backend is running and connected to MongoDB before using features like resume creation, editing, sharing, and AI-assisted upload.
