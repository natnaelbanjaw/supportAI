🚀 Support AI — Autonomous Customer Support SaaS

Support AI is a high-converting, interactive frontend prototype for an AI-powered customer support platform. It demonstrates a complete SaaS user journey—from an engaging landing page with live AI widgets to a multi-tier pricing selection and a dynamic "Company Profile Analyzer" that instantly trains a custom support bot using the Google Gemini API.

✨ Key Features

Live AI Chat Widgets: Interactive hero and sandbox chat interfaces powered by real-time LLM responses.

Company Profile Analyzer: An onboarding wizard that takes a company name, URL, and description, then uses Gemini to synthesize a custom knowledge base.

Post-Setup Dashboard: A simulated client dashboard showing AI resolution metrics, indexed articles, and a live preview of the trained custom widget.

Dynamic Markdown Parsing: The chat interface formats AI responses correctly, handling bold text, italics, and code blocks for a polished user experience.

Modern UI/UX: Built with Tailwind CSS, featuring glassmorphism effects, smooth animations, and a seamless Light/Dark mode toggle.

Single-Page Architecture: Smooth view transitions between the Landing Page, Pricing, Analyzer, and Dashboard using Vanilla JavaScript.

🛠️ Tech Stack

Frontend: HTML5, Vanilla JavaScript, CSS3

Styling: Tailwind CSS (via CDN)

Icons: FontAwesome

AI Integration: Google Gemini API (gemini-3-flash-preview)

🚀 Getting Started

Prerequisites

To run this project locally, you will need an API key from Google AI Studio.

Installation & Setup

Clone the repository (or download the index.html file):

git clone https://github.com/yourusername/support-ai.git
cd support-ai


Add your Gemini API Key:

Open index.html in your favorite code editor.

Locate the callGeminiAPI function (around line 430).

Replace the empty string with your actual API key:

const apiKey = "YOUR_GEMINI_API_KEY_HERE";


Run the application:

Simply double-click the index.html file to open it in your web browser.

Alternatively, use a local server like VS Code's "Live Server" extension for a better development experience.

⚠️ Important Security Note for Production

Currently, the Gemini API key is hardcoded into the frontend JavaScript. Do not deploy this code to a public, production environment as-is.

If you publish this to a live domain, anyone can inspect the source code, extract your API key, and use your quota. Before launching a real startup, you must move the API call to a backend server (e.g., Node.js/Express, Python/FastAPI, or Vercel Serverless Functions) and store the key securely in environment variables.

🌐 Deployment

For testing or portfolio purposes, you can easily deploy this static HTML file using Vercel, Netlify, or GitHub Pages.

If deploying on Vercel:

Drag and drop the project folder into the Vercel dashboard.

Click Deploy.

(Remember the security note above if deploying publicly!)

📄 License

This project is open-source and available under the MIT License.
