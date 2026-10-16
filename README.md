<div align="center">

# 🛒 Amazon Clone

An elegant, desktop-focused frontend clone of the **Amazon.com** homepage built using semantic **HTML5** and pure **CSS3**.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=for-the-badge&logo=font-awesome&logoColor=white)](https://fontawesome.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

[**Explore the Code »**](#-project-structure) · [**Report Bug »**](https://github.com/tanushkaagupta) · [**Request Feature »**](https://github.com/tanushkaagupta)

</div>

---

## 📖 Table of Contents

- [About The Project](#-about-the-project)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Local Development Setup](#-local-development-setup)
- [How to Push to GitHub](#-how-to-push-to-github)
- [Deploy on GitHub Pages](#-deploy-on-github-pages)
- [Future Roadmap](#-future-roadmap)
- [Author](#-author)
- [License](#-license)

---

## 📌 About The Project

This repository contains a static frontend replica of Amazon's classic homepage. It demonstrates:
- Semantic layout structuring with HTML5
- Advanced layout design using CSS Flexbox
- Pixel-aligned navigation bars and dropdowns
- Multi-card showcase grids and hover interactions
- Standard multi-tier e-commerce footers

---

## ✨ Key Features

- **Primary Navigation Bar**:
  - Amazon brand logo
  - Delivery location indicator (India)
  - Custom multi-part search bar with category selector dropdown and search button
  - Account & Lists sign-in shortcut
  - Returns & Orders link
  - Shopping cart icon with item display
- **Secondary Sub-Navbar**:
  - Hamburger menu ("All")
  - Quick action links (*Today's Deals*, *Buy Again*, *Customer Service*, *Registry*, *Gift Cards*, *Sell*)
  - Electronics deals banner
- **Hero Banner**:
  - Full-width promotional banner
  - Localized shopping notice banner with redirection link
- **Product Deal Cards**:
  - Flexible multi-column grid featuring curated shopping boxes
  - Individual cards for PC Deals, Beauty Steals, Toys Under $25, Personal Care, and Office Furniture
  - Highlighting hover outlines and clickable "See more" triggers
- **Multi-Level Footer**:
  - **Panel 1**: "Back to Top" navigation button
  - **Panel 2**: 4-column structured directory (*Get to Know Us*, *Make Money with Us*, *Amazon Payment Products*, *Let Us Help You*)
  - **Panel 3**: Centered branding logo
  - **Panel 4**: Conditions of Use, Privacy Notices, and Copyright line

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic structure and content organization |
| **CSS3** | Flexbox layouts, styling, spacing, and hover states |
| **Font Awesome (v6.6.0)** | Vector icons for search, location, cart, and hamburger menu |

---

## 📁 Project Structure

```plaintext
Amazon web/
│
├── .gitignore       # Git ignore rules for OS and IDE files
├── LICENSE          # MIT Open Source License
├── README.md        # Project documentation & setup instructions
│
├── index.html       # Main webpage structure
├── style.css        # Core styling and Flexbox rules
│
├── logo 1.jpg       # Amazon logo asset
├── 1.jpg            # Hero banner background
├── 2.jpg            # Deals in PC's / Office furniture image
├── 3.jpg            # Beauty steals image
├── 4.jpg            # Toys under $25 image
└── 5.jpg            # Personal care image
```

---

## 🚀 Local Development Setup

To run this project locally without any dependencies or builds:

### Option 1: Direct File Open
1. Clone or download the repository to your computer.
2. Double-click `index.html` to open it in your default browser.

### Option 2: Using VS Code Live Server
1. Open this folder in **Visual Studio Code**.
2. Install the **Live Server** extension by Ritwick Dey.
3. Right-click `index.html` and select **"Open with Live Server"**.

---

## 📤 How to Push to GitHub

To push this project to your GitHub profile, run these simple commands in your terminal:

```bash
# 1. Create a new repository named "amazon-clone" on your GitHub (https://github.com/new)
# (Do not check "Add a README file", .gitignore, or license)

# 2. Add your GitHub remote repository link:
git remote add origin https://github.com/tanushkaagupta/<YOUR-REPO-NAME>.git

# 3. Ensure branch is main:
git branch -M main

# 4. Push your code to GitHub:
git push -u origin main
```

---

## 🌐 Deploy on GitHub Pages

You can host this website for free using **GitHub Pages**:

1. Go to your repository on GitHub.
2. Navigate to **Settings** > **Pages** (in the left sidebar).
3. Under **Build and deployment > Branch**, select `main` and `/ (root)`.
4. Click **Save**.
5. Within 1–2 minutes, your website will be live at:
   `https://tanushkaagupta.github.io/<YOUR-REPO-NAME>/`

---

## 🔮 Future Roadmap

- [ ] Add interactive JavaScript search functionality and dynamic filtering.
- [ ] Add a functional shopping cart increment counter.
- [ ] Implement responsive drawer navigation for mobile and tablet devices.
- [ ] Add smooth scrolling behavior for the "Back to Top" button.

---

## 👩‍💻 Author

**Tanushkaa Gupta**  
GitHub: [@tanushkaagupta](https://github.com/tanushkaagupta)

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.
