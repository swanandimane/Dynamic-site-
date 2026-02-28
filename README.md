# 🚀 Hero Section — HTML & CSS

> *Build something beautiful.* — A modern hero section built with HTML & CSS.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

---

## ✨ Features

- 🎨 Blue gradient full page background
- 🃏 White card hero layout
- 💙 Animated floating cards (float animation)
- 🔵 Primary & Secondary buttons
- 🏢 Brand logos row — Netflix, Spotify, Amazon, Figma

---

## 📁 Folder Structure
```
📁 hero-section/
   ├── 📄 index.html
   └── 🎨 style2.css
```

---

## 🔄 Page Flow
```mermaid
flowchart TD
    A([🌐 Page Loads]) --> B[🌊 Blue Gradient Background]
    B --> C[🃏 White Hero Card]
    C --> D[⬅️ Left Side]
    C --> E[➡️ Right Side]

    D --> D1[📝 Heading — Build something beautiful]
    D1 --> D2[📄 Subtext description]
    D2 --> D3[🔵 Get Started + Learn More Buttons]
    D3 --> D4[🏢 Brands Row\nNetflix - Spotify - Amazon - Figma]

    E --> E1[📦 Floating Card 1]
    E --> E2[📄 Floating Card 2]
    E --> E3[⏰ Floating Card 3]

    style A fill:#1e3c72,color:#fff,stroke:#2563eb
    style B fill:#2a5298,color:#fff,stroke:#2563eb
    style C fill:#fff,color:#111,stroke:#2563eb
    style D fill:#2563eb,color:#fff,stroke:#1e3c72
    style E fill:#2563eb,color:#fff,stroke:#1e3c72
```

---

## 🎨 Design Details

| Feature | Detail |
|---------|--------|
| Background | Dark blue gradient `#1e3c72 → #2a5298` |
| Hero Card | White with rounded corners + shadow |
| Accent Color | Blue `#2563eb` |
| Animation | Cards float up and down infinitely |
| Font | Segoe UI |

---

## ▶️ How to Run
```bash
1. Download both files
2. Keep index.html and style2.css in same folder
3. Open index.html in browser
```

---

> *Built with HTML & CSS only — no frameworks* 💪
