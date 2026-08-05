# ⚡ Muhammad Aun — Creative Developer Portfolio

A modern, animated developer portfolio built with HTML5, Vanilla CSS3, and JavaScript (ES6+), featuring **GSAP 3** and **Locomotive Scroll 4** for smooth-scroll, parallax, and mask-reveal animations. Designed with a minimalist black & white aesthetic, interactive hover elements, and a full-screen lightbox modal for certificate viewing.

---

## 🌟 Key Features & Architecture

- **🎨 Minimalist Black & White Design System**: Clean typography pairing (*Fjalla One* + *Gilroy*), high-contrast layout, and a custom mouse-follower cursor spotlight.
- **⚡ Smooth Locomotive & GSAP Motion**: Locomotive Scroll v4 integrated with GSAP ScrollTrigger for parallax image movement, pinned sections, and scroll-triggered reveals.
- **📱 Fully Responsive Layout**: Fluid typography (`vw`-based sizing) adapting across mobile, tablet, and desktop breakpoints.
- **🎓 Certifications Section**: Numbered, editorial-style certificate list with:
  - **(01) AI Developer** — *Be Practical With AI, Coursera*
  - **(02) Project Management** — *Plan with purpose. Execute with precision. Deliver with confidence, Coursera*
- **🖼️ Full-Screen Lightbox Modal**: Click any certificate title or thumbnail to view the full-resolution image in a dark blur backdrop, closable via the `×` button, backdrop click, or `Escape` key.
- **📩 Interactive Contact Form**: Client-side submit handler with an inline "Thank You" confirmation card (`#submit-success`), plus quick links to LinkedIn and email.
- **🔝 Smooth Navigation**: Nav links and logo trigger smooth Locomotive scroll-to-section behavior; footer "Back to Top" control included.

---

## 🛠️ Tech Stack & Libraries

| Layer | Technologies & Tools |
|---|---|
| **Frontend Core** | HTML5, Vanilla CSS3, JavaScript (ES6+) |
| **Animation Engines** | GSAP 3, GSAP ScrollTrigger, Locomotive Scroll 4 |
| **UI Icons & Fonts** | RemixIcon, Google/Custom Fonts (*Fjalla One*, *Gilroy*) |
| **Hosting & Deployment** | Vercel |

---

## 📂 Project Directory Structure

```text
port/
├── index.html                  # Main portfolio HTML structure
├── style.css                   # Layout, responsive design & animation styles
├── script.js                   # Locomotive Scroll, GSAP timelines, modal & form logic
├── README.md                   # Project documentation
└── images/                     # Portfolio visual assets
    ├── AI-cert.jpg             # AI Developer Certificate (Coursera)
    ├── mng.png                 # Project Management Certificate (Coursera)
    └── ...                     # Additional site imagery
```

---

## 💻 Local Setup & Development Guide

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
   cd YOUR-REPO
   ```

2. **Launch a local development server**:
   Using Python 3:
   ```bash
   python3 -m http.server 3000
   ```
   Or using Node.js `npx`:
   ```bash
   npx serve .
   ```

3. **View the live project**:
   Open your browser and navigate to `http://localhost:3000/`.

---

## 🌐 Deploying to Production

This project is zero-dependency static HTML/CSS/JS and deploys instantly to **Vercel**, **Netlify**, or **GitHub Pages**.

### Deploying via Vercel:
```bash
npx vercel --prod
```
Or connect your GitHub repo directly at [vercel.com](https://vercel.com) for automatic deploys on every push.

---

## 👤 Author

**Muhammad Aun** — *Creative Developer*
- **Certifications**: AI Developer & Project Management (Coursera)
- **Location**: Dunyapur, Pakistan
- **Email**: [aun949871@gmail.com](mailto:aun949871@gmail.com)
- **LinkedIn**: [muhammad-aun-368293384](https://www.linkedin.com/in/muhammad-aun-368293384)

---

*© 2026 Aun. All Rights Reserved.*
