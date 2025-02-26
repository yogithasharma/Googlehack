# Googlehack
# **GoogleHack - Online Code Editor**  

GoogleHack is an online code editor that allows users to write, edit, and execute code in real time. It integrates OpenAI's GPT to assist with code completion and suggestions.

---

## **🚀 Features**  
✅ **Real-time Code Execution** – Write and run code instantly.  
✅ **Multi-language Support** – Supports multiple programming languages.  
✅ **AI Assistance** – Uses OpenAI's GPT for code suggestions.  
✅ **User Authentication** – Secure login system for users.  
✅ **Syntax Highlighting** – Enhanced code readability.  

---

## **🛠️ Tech Stack**  
### **Frontend**  
- React  
- Vite  
- Tailwind CSS  

### **Backend**  
- Node.js  
- Express.js  
- OpenAI API  

---

## **📂 Project Structure**  
Googlehack/ │── frontend/ # React code editor UI
│── backend/ # Node.js server
│ ├── server.js # Main backend server
│ ├── routes/ # API routes
│ ├── controllers/ # Request handlers
│── package.json # Dependencies and scripts
│── README.md # Project documentation

yaml
Copy
Edit

---

## **🔧 Installation & Setup**  

### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/yogithasharma/Googlehack.git
cd Googlehack
2️⃣ Install Dependencies
sh
Copy
Edit
cd frontend
npm install
cd ../backend
npm install
3️⃣ Set Up Environment Variables
Create a .env file inside the backend/ folder and add:

sh
Copy
Edit
OPENAI_API_KEY=your_openai_api_key
PORT=5000
4️⃣ Run the Project
Start Backend
sh
Copy
Edit
cd backend
node server.js
Start Frontend
sh
Copy
Edit
cd frontend
npm run dev
Now, open http://localhost:5173 in your browser. 🚀

🤖 API Endpoints
Method	Endpoint	Description
POST	/chatgpt	Sends prompt to GPT-3
🤝 Contributing
Fork the repository
Create a new branch (git checkout -b feature-branch)
Commit your changes (git commit -m "Added new feature")
Push to the branch (git push origin feature-branch)
Open a Pull Request
📜 License
This project is licensed under the MIT License.

📩 Contact
For any queries, reach out to:
📧 Email: your-email@example.com
🔗 GitHub: yogithasharma

mathematica
Copy
Edit

### **5️⃣ Save and Close the File**  
If you're using Notepad, press **Ctrl + S** to save and then close.  
If using VS Code, press **Ctrl + S**, then close the file.

### **6️⃣ Add and Commit the README.md File**  
Run these commands to track and push the README file to GitHub:  
```sh
git add README.md
git commit -m "Added README file"
git push origin main
