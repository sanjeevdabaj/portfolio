# Modern Developer Portfolio Website

A sleek, responsive, and high-performance personal portfolio website built with modern HTML5, Tailwind CSS, and JavaScript. Inspired by clean developer portfolios on Netlify.

---

## 🚀 Quick Start (Local Preview)

### Method 1: Direct File Open (Easiest)
Simply double-click `index.html` in Windows Explorer, or right-click `index.html` and choose **Open with > Chrome / Edge / Brave / Firefox**.

### Method 2: Local HTTP Server (Optional)
If you want to run a local server:
```powershell
# Using Node's built-in npx
npx serve .

# Or using Python 3
python -m http.server 3000
```
Then visit `http://localhost:3000` in your browser.

---

## 📁 Project Structure

```
portfolio-website/
├── index.html        # Main semantic markup & all sections
├── style.css         # Glassmorphism, animations, glow orbs, scrollbar
├── script.js         # Typewriter effect, theme switcher, project filter, contact form
└── README.md         # Documentation & deployment guide
```

---

## 🎨 Features & Highlights

- **Hero Section**: Dynamic typewriter text animation, status indicator ("Available for work"), social links, and interactive developer code window.
- **Dark / Light Theme Toggle**: Seamless transition with local storage persistence.
- **About Me & Stats**: Clean narrative and Bento-style highlight cards.
- **Skills Grid**: Organized by Frontend, Backend, Databases, and Tools with icons.
- **Interactive Projects Showcase**: Categorized filtering (All, Full-Stack, Frontend, Backend/AI) with live demo & GitHub repository links.
- **Experience & Education**: Clean vertical timeline structure.
- **Contact Form**: Interactive form with input validation and feedback toast notifications.
- **Mobile Responsive**: Custom hamburger menu drawer for smooth mobile viewing.

---

## 🛠️ How to Customize

1. **Personal Information**:
   - Open `index.html` and update your name, email, and social links (GitHub, LinkedIn, Twitter).
2. **Typewriter Roles**:
   - In `script.js`, edit the `roles` array to change the animated titles in the Hero section.
3. **Projects**:
   - In `index.html` under the `#projects` section, replace project titles, descriptions, tech badges, and demo/GitHub links.
4. **Resume**:
   - Put your resume PDF in this folder (e.g. `resume.pdf`) and change `href="#contact"` in the Resume button to `href="resume.pdf"` with `download`.

---

## 🌐 Free 2-Minute Deployment to Netlify

1. Go to [Netlify Drop](https://app.netlify.com/drop).
2. Drag and drop the `portfolio-website` folder onto the page.
3. Your portfolio is instantly live with a free custom `https://yourname.netlify.app` URL and free SSL!
