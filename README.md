# F🏠 Flatmate Project
This project is designed to streamline the process of finding and allocating ideal flatmates using an integrated AI system. It is structured with three main components:

Frontend – Built with React (or relevant framework)

Backend – Handles APIs and business logic

Chatbot – An AI-powered assistant to guide users

🚀 How to Run the Project Using PowerShell
Follow the steps below to run the entire project on your local machine:

⚠️ Make sure you have Node.js, npm, and Python installed before starting.

1. Start the Frontend
powershell

cd frontend
npm i          # Only for the first-time setup
npm run dev

This will start the frontend on the default local development server (usually http://localhost:5173 or http://localhost:3000 depending on your setup).

2. Start the Backend
Open a new PowerShell terminal, then run:

powershell


cd backend
npm run start

Make sure any required .env files or environment variables are configured.

3. Start the Chatbot
Again, open another PowerShell terminal, then run:

cd chatbot
python app.py

Ensure all Python dependencies are installed (pip install -r requirements.txt) if running for the first time.

✅ Project Structure
bash
Copy
Edit
/frontend  → UI and client-side logic  
/backend   → Server-side APIs and database logic  
/chatbot   → AI chatbot logic using Python
📬 Contact
For issues or suggestions, please feel free to open an issue or reach out!
