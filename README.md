# Tursina Yisehak — Personal Portfolio

A modern, responsive personal portfolio website built with pure **HTML**, **CSS**, and **JavaScript** — no frameworks, no build tools. Features glassmorphism design, gradient accents, dark/light theme toggle, smooth animations, and a fully working contact form.

🌐 **Live Site:** [tuyy-99.github.io/portfolio2](https://tuyy-99.github.io/portfolio2) *(update after deploying)*

---

## ✨ Features

- **Glassmorphism UI** — frosted glass cards with backdrop blur throughout
- **Dark / Light Theme** — toggle persists across sessions via `localStorage`
- **Typing Animation** — rotating phrases in the hero section
- **Animated Background** — floating gradient blobs
- **Scroll Animations** — elements fade in as you scroll
- **Skill Chips** — clean pill-style tech tags, no fake percentages
- **Real Projects** — cards pulled directly from actual GitHub repositories
- **Contact Form** — client-side validation with success feedback
- **Fully Responsive** — mobile, tablet, and desktop layouts
- **Zero Dependencies** — no npm, no bundler, just open `index.html`

---

## 🗂️ Project Structure

```
portfolio/
├── index.html       # Full page structure & content
├── style.css        # All styles — variables, glassmorphism, responsive
├── script.js        # Theme toggle, typing effect, scroll animations
├── pp.jpg           # Profile photo (add your own)
└── README.md        # You are here
```

---

## 🛠️ Tech Stack

| Layer      | Technology                          |
|------------|-------------------------------------|
| Markup     | HTML5                               |
| Styling    | CSS3 (custom properties, grid, flex)|
| Logic      | Vanilla JavaScript (ES6+)           |
| Icons      | Font Awesome 6                      |
| Fonts      | Google Fonts — Inter, Fira Code     |

---

## 🚀 Getting Started

No installation or build step needed.

```bash
# Clone the repo
git clone https://github.com/tuyy-99/portfolio2.git

# Open in browser
open index.html
```

Or just drag `index.html` into any browser.

---

## 📸 Adding Your Profile Photo

Place your photo in the root folder and name it `pp.jpg`:

```
portfolio/
└── pp.jpg   ← your photo here
```

The image is displayed as a circle in the hero section. Recommended size: **400×400px** or larger, square crop.

---

## 🎨 Customization

All design tokens live at the top of `style.css` as CSS variables:

```css
:root {
  --gradient: linear-gradient(135deg, #a78bfa, #60a5fa, #34d399);
  --radius: 16px;
  --transition: all 0.3s ease;
}
```

**To change the color scheme** — update `--gradient` in `:root`.  
**To add a dark theme color** — edit the `[data-theme="dark"]` block.  
**To add a light theme color** — edit the `[data-theme="light"]` block.

---

## 📄 Sections

| Section   | Description                                              |
|-----------|----------------------------------------------------------|
| Hero      | Name, typed role, CTA buttons, social links, avatar      |
| About     | Bio, info cards, stats                                   |
| Skills    | Grouped chip-style tags — Languages, Databases, Web & Tools |
| Projects  | Real GitHub project cards with links and tech tags       |
| Contact   | Email form + direct links to email, LinkedIn, GitHub     |

---

## 📬 Contact

| Platform | Link |
|----------|------|
| Email    | [tursinayisehak@gmail.com](mailto:tursinayisehak@gmail.com) |
| LinkedIn | [tursina-yisehak-7a9942358](https://www.linkedin.com/in/tursina-yisehak-7a9942358) |
| GitHub   | [tuyy-99](https://github.com/tuyy-99) |

---

## 📝 License

This project is open source and free to use for personal and educational purposes.  
If you use it as a base for your own portfolio, a credit or star is appreciated. ⭐

---

<p align="center">Designed & built by <strong>Tursina Yisehak</strong> · Software Engineering Student · Ethiopia</p>
