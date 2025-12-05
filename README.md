# Crowd Reply - Task Management Assessment
## Tech Stack
- **Backend**: Node.js, Express, MongoDB, Mongoose, TypeScript, JWT.
- **Frontend**: Next.js (App Router), TypeScript, Tailwind CSS, Axios.
## Getting Started
### Prerequisites
- Node.js (v18+)
- MongoDB (Local or Atlas)
### Installation
1.  **Clone the repository**
2.  **Backend Setup**:
    ```bash
    cd backend
    npm install
    # Create .env file (see .env.example)
    npm run dev
    ```
3.  **Frontend Setup**:
    ```bash
    cd frontend
    npm install
    # Create .env.local file
    npm run dev
    ```
### Environment Variables
**Backend (.env)**:
```env
PORT=4000
MONGO_URI=mongodb://localhost:27017/mern-assessment
JWT_SECRET=your_jwt_secret
```
**Frontend (.env.local)**:
```env
NEXT_PUBLIC_API_URL=http://localhost:4000/api
```

## Note on Search Functionality

The search bar on the Tasks page provides **client-side filtering** for the currently loaded tasks. It filters tasks by content or platform name. For a full database search, 
backend implementation would be required.not setup because it's not mentioned in the requirements.

