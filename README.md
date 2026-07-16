# Employee Profile Dashboard

A clean, modern, and highly responsive Employee Profile Dashboard built using semantic HTML, pure CSS, and vanilla JavaScript. This project demonstrates core frontend web development principles, structured according to enterprise best practices.

---

## 🚀 Live Demo & Preview
* **Desktop View:** Features a sticky left-side navigation sidebar, top actions bar, horizontal profile card, and side-by-side informational panels.
* **Tablet View:** Adjusts component scaling and transitions layout cards using Flexbox and CSS Grid.
* **Mobile View:** Stacks all layout sections vertically with horizontal scrolling menus and tabs to fit narrow viewport widths.

---

## 🛠️ Concepts Demonstrated

### 1. 🏷️ Semantic HTML5
Utilizes meaningful layout tags that explain their content structure to browsers, search engines (SEO), and screen readers (Accessibility):
* `<aside>` for site navigation menus.
* `<main>` for core content wrapper.
* `<header>` for header rows.
* `<nav>` for list of links.
* `<section>` & `<article>` for layout cards.
* `<dl>`, `<dt>`, & `<dd>` for key-value description lists.

### 2. 📦 CSS Box Model
Custom sizes, boundaries, and element spacing parameters:
* `box-sizing: border-box` set globally to lock width sizing calculations.
* Custom padding inside cards and margins between components.
* Rounded borders using `border-radius`.

### 3. 🔲 Flexbox (Flexible Box Layout)
Controls single-dimension alignments:
* Vertical elements stacking in the sidebar.
* Horizontal row alignment in the top bar using `justify-content: space-between`.
* Wrapping skills tags dynamically on small screens using `flex-wrap: wrap`.

### 4. 🗂️ CSS Grid
Controls multi-dimension layouts:
* **Page Layout:** Switches to a `240px 1fr` structure on desktops.
* **Details Grid:** Switches from stacked blocks to a `1fr 1fr` grid on screens wider than `768px`.

### 5. 📱 Mobile-First Responsive Design & Media Queries
Styles are written for mobile viewports by default. Layout upgrades for larger screens are added progressively using `min-width` media queries:
* Default (Mobile)
* `@media (min-width: 768px)` (Tablet Breakpoint)
* `@media (min-width: 1024px)` (Desktop Breakpoint)

### 6. ⚙️ Interactive Tabs (JavaScript)
A lightweight JavaScript function (`showTab`) toggles hidden CSS classes (`.hidden`) and active tab states (`.active-tab`) to switch views on-the-fly without loading new HTML pages.

---

## 📁 Project Structure
📁 employee-dashboard/ │ ├── 📄 index.html # Layout structure and script logic 
                          ├── 📄 dashboard.css # Mobile-first CSS stylesheet 
                            └── 🖼️ profile.jpeg # Employee profile avatar image



---
## 💻 Setup & Installation
### Prerequisites
* A standard modern web browser (Google Chrome, Microsoft Edge, Firefox, Safari).
* [Optional] **Visual Studio Code** with the **Live Server** extension installed.
### How to Run Locally
1. Download or clone this repository to your computer:
   ```bash
   https://github.com/saicharanisigntech-svg/Employee-Dashboard.git
2. Make sure you have your profile picture inside the folder named exactly profile.jpeg.
3. Open VS Code → File → Open Folder → Select the project directory.
4. Right-click index.html and click "Open with Live Server" (or double-click the file to open directly in a browser).
