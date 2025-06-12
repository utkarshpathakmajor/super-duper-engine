Growth India
DOCTYPE html>
<html>
<head><meta charset="UTF-8">

  <title>Growth India</title>
  <link rel="stylesheet" href="style.css" />
</head>

<body><button onclick="toggleMode()">🌓 Toggle Light/Dark Mode</button>

  <h1>Welcome to Growth India</h1>
  <p>Empowering Rural Youth with AI</p>

  <button onclick="showMessage()">Click Me</button>

  <script src="script.js"></script>
</body>
</html>
<section id="why">
  <h2>Why Growth India?</h2>
  <p>India's rural youth have untapped potential. Growth India bridges the gap using AI tools, digital education, and local innovation.</p>
</section>
<section id="vision">
  <h2>Our Vision</h2>
  <p>To build AI-powered rural learning centers across India that offer modern education, skill training, and tech-based livelihood support.</p>

  <h3>Pilot Village: Pathkhauli</h3>
  <p>We begin from Pathkhauli, Ayodhya — a model village for digital innovation, student-led AI labs, and 24/7 community access.</p>
</section>
<section id="join">
  <h2>Join the Movement</h2>
  <p>We are inviting students, teachers, developers & donors to be part of the Growth India journey. Together, we build digital Bharat.</p>

  <button onclick="showJoinMessage()">Join Us</button>

  <h3>Coming Soon: AI Gram Assistant 🤖</h3>
  <p>A local-language chatbot to answer students' questions, support farmers, and connect communities — in development phase!</p>
</section>
body {
  font-family: Arial, sans-serif;
  text-align: center;
  padding: 50px;
  background: #f0f0f0;
}

button {
  padding: 10px 20px;
  font-size: 18px;
  background-color: #2e8b57;
  color: white;
  border: none;
  border-radius: 8px;
  cursor: pointer;
}

button:hover {
  background-color: #246b45;
}
section {
  margin-top: 40px;
  padding: 20px;
  background: #ffffff;
  border-radius: 12px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

h2 {
  color: #2e8b57;
}
h3 {
  color: #444;
  margin-top: 20px;
}
#join button {
  margin-top: 10px;
}
.dark-mode {
  background-color: #121212;
  color: white;
}

.dark-mode section {
  background: #1e1e1e;
  box-shadow: 0 0 10px rgba(255,255,255,0.1);
}

.dark-mode button {
  background-color: #444;
}
console.log('Hello!');
function showMessage() {
  alert("🚀 Jai Hind! You clicked the Growth India button.");
}
function showJoinMessage() {
  alert("Thanks for your interest! We’ll connect you soon to Growth India.");
}
function toggleMode() {
  document.body.classList.toggle("dark-mode");
}

