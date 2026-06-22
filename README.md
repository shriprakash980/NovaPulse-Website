# 🚀 NovaPulse — Premium Static Website

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Mobile--First-6c63ff?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-34d399?style=for-the-badge)

**A modern, premium-looking multipage static website built with pure HTML5, CSS3 & vanilla JavaScript.**

[Live Demo](#) · [Report Bug](https://github.com/shriprakash980/NovaPulse-Website/issues) · [Request Feature](https://github.com/shriprakash980/NovaPulse-Website/issues)

</div>

---

## ✨ Overview

NovaPulse is a sleek startup landing page template featuring **glassmorphism design**, **blue-purple gradients**, **smooth scroll animations**, and a **fully responsive** layout. It's crafted to look and feel like a premium SaaS product site — no frameworks, no dependencies, just clean code.

---

## 📸 Screenshots

### 🏠 Home Page
> Hero section with animated floating cards, gradient text, CTA buttons, and live stats.

### 📖 About Page
> Company story, core values grid, team section with real photos, and a stats bar.

### ⚙️ Services Page
> Service cards, 4-step process workflow, transparent pricing tiers with a featured plan.

### 📬 Contact Page
> Full contact form with budget dropdown, contact info cards, and an FAQ section.

---

## 🎨 Design Features

| Feature | Implementation |
|---------|---------------|
| **Glassmorphism** | `backdrop-filter: blur()` with semi-transparent backgrounds & subtle borders |
| **Gradient Theme** | Blue → Purple → Cyan gradient palette across all accents |
| **Animated Orbs** | Floating background orbs with CSS keyframe animations |
| **Scroll Animations** | Intersection Observer API for fade-in-on-scroll effects |
| **Floating Cards** | Animated hero cards with smooth `float` keyframes |
| **Hover Effects** | Scale transforms, glow shadows, gradient reveals on cards |
| **Sticky Navbar** | Transparent → frosted glass on scroll with JS toggle |
| **Mobile Menu** | Pure CSS hamburger toggle using the checkbox hack |
| **Custom Scrollbar** | Styled scrollbar matching the purple theme |
| **Google Fonts** | [Inter](https://fonts.google.com/specimen/Inter) — modern, clean typography |

---

## 📁 Project Structure

```
NovaPulse-Website/
├── index.html            # Home page
├── about.html            # About page
├── services.html         # Services page
├── contact.html          # Contact page
├── README.md             # Project documentation
├── css/
│   └── style.css         # Complete design system (~1100 lines)
└── images/
    ├── team-1.png        # Team member — Alex Chen
    ├── team-2.png        # Team member — Maria Santos
    ├── team-3.png        # Team member — James Wright
    └── team-4.png        # Team member — Priya Patel
```

---

## 🛠️ Tech Stack

- **HTML5** — Semantic markup with proper heading hierarchy and accessibility attributes
- **CSS3** — Custom properties, CSS Grid, Flexbox, `clamp()`, `backdrop-filter`, media queries
- **JavaScript** — Intersection Observer for scroll animations, navbar scroll detection
- **Google Fonts** — Inter (300–900 weights)

> ⚡ **Zero dependencies.** No frameworks, no build tools, no npm. Just open `index.html` in a browser.

---

## 🚀 Getting Started

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/shriprakash980/NovaPulse-Website.git
   ```

2. **Open in browser**
   ```bash
   cd NovaPulse-Website
   open index.html        # macOS
   start index.html       # Windows
   xdg-open index.html    # Linux
   ```

That's it — no installation or build steps required!

### Using a Local Server (Optional)

For the best experience with no CORS issues:

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve .

# VS Code
# Install "Live Server" extension → Right-click index.html → "Open with Live Server"
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Target | Layout Changes |
|-----------|--------|----------------|
| `> 1024px` | Desktop | Full multi-column grids, floating hero cards visible |
| `768px – 1024px` | Tablet | 2-column grids, hero visual hidden, stacked about section |
| `< 768px` | Mobile | Single-column grids, hamburger menu, stacked CTAs |
| `< 480px` | Small Mobile | Stacked stats, centered hero stats |

---

## 📄 Pages Overview

### 🏠 Home (`index.html`)
- Animated hero with gradient title, CTA buttons, and live stats
- 6 feature cards with icon-to-gradient hover effect
- 3 service preview cards with arrow links
- 3 testimonial cards with star ratings
- CTA banner section
- Full footer with social links

### 📖 About (`about.html`)
- Page hero with breadcrumb navigation
- Stats bar (150+ projects, 50+ team, 12+ years, 30+ countries)
- Company story with highlights grid
- 4 core values with rotating icon hover
- 4 team members with real AI-generated photos
- Join-the-team CTA

### ⚙️ Services (`services.html`)
- 6 detailed service cards (Web, Mobile, AI, UI/UX, Cloud, Data)
- 4-step process workflow with connected timeline
- 3-tier pricing (Starter $2,999 / Professional $9,999 / Enterprise Custom)
- Featured "Most Popular" pricing badge

### 📬 Contact (`contact.html`)
- 4 contact info cards (Email, Phone, Address, Social)
- Full contact form (name, email, phone, budget, subject, message)
- Budget range dropdown selector
- 6 FAQ cards addressing common client questions

---

## 🎯 CSS Architecture

The stylesheet uses a well-organized design system approach:

```
style.css
├── Design System (CSS custom properties)
├── Reset & Base styles
├── Utility classes
├── Background orbs animation
├── Navbar (sticky + glass)
├── Buttons (primary, secondary, sizes)
├── Hero section
├── Glass card component
├── Features grid
├── Services grid
├── About / Story section
├── Values grid
├── Team grid
├── Testimonials
├── CTA section
├── Contact form
├── Page hero (inner pages)
├── Stats bar
├── Pricing cards
├── Process / workflow
├── Footer
├── Keyframe animations
├── Responsive — Tablet (≤1024px)
├── Responsive — Mobile (≤768px)
├── Responsive — Small mobile (≤480px)
└── Scrollbar & selection styling
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Shri Prakash**

- GitHub: [@shriprakash980](https://github.com/shriprakash980)

---

<div align="center">

⭐ **Star this repo if you found it useful!** ⭐

Made with ❤️ using pure HTML, CSS & JS

</div>
