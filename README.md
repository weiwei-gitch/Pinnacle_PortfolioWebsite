# 🕷️ Roshni Sukhnani — Personal Portfolio Website

> A Spider-Man inspired dark-themed 3D personal portfolio website built with pure HTML, CSS, and JavaScript.

---

## 🌐 Live Demo

https://weiwei-gitch.github.io/Pinnacle_PortfolioWebsite/

---

## 📸 Preview

![Portfolio Preview](preview.png)

---

## ✨ Features

- 🕸️ **Spider-Web Aesthetics** — Organic draping webs across the hero section and SVG web dividers between every section, with hanging threads and dewdrop dot details
- 🕷️ **Crawling Spider** — An animated spider that slowly crawls across the page on its own path
- 🌐 **Background Web Mesh** — Full-screen canvas-drawn web network with radial corner webs and subtle strand patterns
- 🃏 **3D Card Tilt** — Every project, skill, stat, and cert card tilts in 3D following your mouse movement
- 🪡 **Hanging Cards** — Project cards hang from web threads at varying heights, simulating weight and depth
- 📸 **Hanging Photo** — Profile photo suspended from a glowing web thread with corner web decorations
- 🎞️ **Scroll Reveal Animations** — Every section pops in with directional fade/slide animations as you scroll
- 🌊 **Parallax Web Canvas** — Background web shifts depth as you scroll down the page
- 📱 **Fully Responsive** — Works on mobile, tablet, and desktop
- ⚡ **Zero Dependencies** — No frameworks, no build tools — pure HTML, CSS, JS

---

## 🗂️ Sections

| Section | Description |
|---|---|
| **Hero** | Name, role, tags, CTA buttons, hanging profile photo |
| **About** | Bio + animated stat cards (internships, projects, hackathons) |
| **Skills** | 4 skill categories with hover-glow tags |
| **Projects** | 6 projects hanging from web threads in a 2-column grid |
| **Experience** | Timeline of 3 simultaneous internships |
| **Certifications** | 3 training programs and certifications |
| **Activities** | Hackathon achievements, sports, arts, education |
| **Contact** | Direct links to email, GitHub, and LinkedIn |

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Structure and semantic markup |
| **CSS3** | Animations, 3D transforms, glassmorphism, gradients |
| **JavaScript (Vanilla)** | Canvas web drawing, scroll reveal, spider animation, 3D tilt |
| **Google Fonts** | Space Grotesk + Space Mono |
| **SVG** | Web dividers, corner decorations, spider silhouette |
| **Canvas API** | Background web mesh and radial corner webs |
| **Intersection Observer API** | Scroll-triggered reveal animations |

---

## 🚀 Getting Started

### Run Locally

No installation needed. Just open the file in your browser:

```bash
# Clone the repo
git clone https://github.com/weiwei-gitch/portfolio.git

# Navigate into the folder
cd portfolio

# Open in browser
open index.html
# or just double-click index.html
```

### Deploy on GitHub Pages

1. Push the repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://weiwei-gitch.github.io/portfolio`

### Deploy on Vercel

1. Go to [vercel.com](https://vercel.com)
2. Click **Add New Project → Import Git Repository**
3. Select your repo and deploy
4. Done — live in seconds!

---

## 📁 Project Structure

```
portfolio/
│
├── index.html        # Main portfolio file (all-in-one)
├── README.md         # Project documentation
└── resume.pdf        # (Optional) Add your resume PDF here
```

> The entire portfolio is self-contained in a single `index.html` file — your photo is embedded as base64, so no external image files are needed.

---

## 🎨 Color Palette

| Color | Hex / Value | Usage |
|---|---|---|
| Deep Black | `#000005` | Page background |
| Dark Navy | `#05080f` – `#0d1428` | Section backgrounds |
| Steel Blue | `#7bb8ff` | Accent, web threads, glows |
| Soft Blue | `#4a90d9` | Button gradients |
| Purple | `#8b5cf6` | Secondary accent |
| Teal | `#2dd4bf` | Tertiary accent |
| Silver | `#c8d8f0` | Body text |
| Web White | `rgba(220,235,255,0.85)` | Web strands and threads |

---

## 🧩 Customization

### Update Contact Links
In `index.html`, find the contact section and update:
```html
<a href="mailto:your@email.com" ...>
<a href="https://github.com/yourusername" ...>
<a href="https://linkedin.com/in/yourprofile" ...>
```

### Add Resume Download
Place your `resume.pdf` in the same folder and add a button:
```html
<a href="resume.pdf" class="btn btn-g" download>↓ Resume</a>
```

### Change Profile Photo
Replace the base64 image in the `<img>` tag inside the hero section with your new photo's base64 string, or swap to a file path:
```html
<img src="your-photo.jpg" alt="Your Name" class="hero-photo"/>
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋‍♀️ Author

**Roshni Sukhnani**
- 📧 [roshnisukhnani@gmail.com](mailto:roshnisukhnani@gmail.com)
- 💻 [github.com/weiwei-gitch](https://github.com/weiwei-gitch)
- 🔗 [LinkedIn](https://www.linkedin.com/in/roshni-sukhnani-a8a854377)

---

> *"A driven and detail-oriented Engineering undergraduate committed to delivering quality work through a blend of academic knowledge, creative thinking, and a team-spirited attitude."*
