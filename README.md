🌐 Personal Portfolio Website – Siri Chandana

A modern, responsive personal portfolio website built using HTML, Tailwind CSS, and Node.js (Express).
This portfolio showcases my education, experience, certifications, projects, and provides an easy way to connect with me online.

The project also includes a backend Express server integrated with the Groq LLM API for future AI-powered features.

✨ Features

🎨 Modern UI/UX

Dark theme with gradients

Fully responsive (mobile, tablet & desktop)

Clean card-based layout

📄 Multiple Sections

Home

Education

Experience

Certifications

Projects

Contact Me

📜 Certificate & Resume Viewer

Open PDFs and images in new tabs

Organized internship and certification records

⚡ Fast & Lightweight

Static frontend served via Express

Optimized CSS and layouts

🤖 AI Chat Backend (Optional)

Express server integrated with Groq API

Ready for chatbot or AI assistant extensions

🛠️ Tech Stack
Frontend

HTML5

CSS3

Tailwind CSS

Responsive Design

Backend

Node.js

Express.js

Groq API

dotenv

CORS

📂 Project Structure
portfolio-website/
│
├── index.html              # Home page
├── education.html          # Education details
├── experience.html         # Work & internship experience
├── certifications.html     # Certifications & achievements
├── projects.html           # Projects showcase
├── extracurriculars.html  # Contact Me page
│
├── certificates/           # Images, PDFs, resume
│
├── server.js               # Express backend server
├── package.json            # Project dependencies
├── .env                    # API keys (not committed)
└── README.md               # Project documentation

🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/your-username/portfolio-website.git
cd portfolio-website

2️⃣ Install Dependencies
npm install

3️⃣ Setup Environment Variables

Create a .env file in the root directory:

GROQ_API_KEY=your_groq_api_key_here

4️⃣ Start the Server
npm start

5️⃣ Open in Browser
http://localhost:10000

🧠 AI Chat API (Optional Feature)

This project includes an Express endpoint for AI-based chat using Groq LLM.

Endpoint:

POST /chat


Request Body Example:

{
  "messages": [
    { "role": "user", "content": "Hello!" }
  ]
}


The backend is ready to be connected to a frontend chat UI.

📸 Screenshots (Optional)

You can add screenshots of your website here later to improve repo visibility.

📄 Resume & Certificates

Resume available directly from the homepage

All certificates stored securely in the certificates/ folder

Internship offer letters and completion certificates included

📍 About Me

Yerra Siri Chandana
🎓 B.Tech CSE (2nd Year) – Lendi Institute of Technology
💻 Interests: Web Development, Programming (C, Python)
📊 CGPA: 9.57

🔗 Connect With Me

💼 LinkedIn:
https://www.linkedin.com/in/siri-chandana-yerra-32a987322

💻 GitHub:
https://github.com/sirichandana-11

📧 Email:
yerrasirichandana11@gmail.com

⭐ Future Enhancements

AI-powered chatbot on the portfolio

Project filtering & animations

Blog section

Admin dashboard to update content dynamically

📝 License

This project is open-source and available for personal and educational use.
