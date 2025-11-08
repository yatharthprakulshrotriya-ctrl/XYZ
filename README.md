please consider frontend.zip and node_modules as the complete frontend file
Run instructions to include in README

Backend setup

cd backend

cp .env.example .env (or create .env and fill MONGODB_URI and JWT_SECRET)

npm install

Start MongoDB (locally) or ensure Atlas connection

npm start

Frontend setup

cd frontend

npm install

npm start

Running both locally (two terminals)

Terminal 1: cd backend && npm start

Terminal 2: cd frontend && npm start

API base URL adjustments

If the frontend needs to reach the backend at a specific URL, update the baseURL in the frontend API wrapper accordingly (e.g., http://localhost:5000/api) API Key is XYZ
