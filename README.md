🎨 Abhinav Shinesh - Creative Developer Portfolio

A high-performance, static portfolio website designed with a Neo-Brutalist / Sketchbook aesthetic. This project showcases my work in AI/ML and Full Stack Development using a unique visual style that blends professional technical data with hand-drawn doodle elements.

✨ Key Features

Zero-Backend Architecture: The entire site runs on static HTML, CSS, and Vanilla JavaScript. No database or server management required.

Dynamic GitHub Integration: Automatically fetches and displays my latest public repositories using the GitHub User API.

Static "Dev Notebook": A built-in blogging system that loads daily logs from a local JSON array, allowing for instant updates without a CMS.

Responsive Design: Fully fluid layout that adapts to mobile, tablet, and desktop screens using CSS Grid and Flexbox.

Custom Aesthetics: Features a noise-texture background, 'Gloria Hallelujah' doodle typography, and CSS-drawn notebook elements.

🛠️ Tech Stack

Core: HTML5, CSS3, Vanilla JavaScript (ES6+)

Fonts: Space Grotesk (Headings), Inter (Body), JetBrains Mono (Code), Gloria Hallelujah (Doodles).

Icons: Inline SVGs (Feather Icons style).

Hosting: Optimized for GitHub Pages / Netlify.

🚀 How to Use & Customize

1. Setup

Clone the repository or download the files. No npm install or build steps are needed. Just open index.html in your browser.

2. Updating Daily Logs

To add a new entry to the "Daily Dev Notebook," open index.html and scroll to the bottom <script> tag. Add a new object to the myLogs array:

const myLogs = [
    // ... existing logs
    {
        date: "2025-03-01", 
        title: "New Update", 
        content: "Write your update here..."
    }
];


3. GitHub Projects

To fetch projects from a different GitHub account, find the fetchProjects function in index.html and replace vetavaliyan with your username:

const res = await fetch('[https://api.github.com/users/YOUR_USERNAME/repos?sort=updated&per_page=6](https://api.github.com/users/YOUR_USERNAME/repos?sort=updated&per_page=6)');


🌍 Deployment

This site is ready for GitHub Pages:

Upload index.html to a public GitHub repository.

Go to Settings > Pages.

Under Source, select main branch.

Your site will be live at https://your-username.github.io/repo-name.

📄 License

This project is open source and available for personal use.
