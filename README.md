# Strike Hackathon

**CoderArmy CSS Hackathon 2025**  
A landing site built for **Strike** — a modern learning platform for computer science, web development, AI, Devops and more.

Live Demo: [https://rahul17singla.github.io/strike-hackathon](https://rahul17singla.github.io/strike-hackathon/)  
(Hosted via GitHub Pages)

---

## 🧱 Project Structure

strike-hackathon/
├── images/ ← assets (logos, course images, backgrounds)
├── index.html ← main HTML page
└── styles.css ← all CSS styling

-   **index.html**: Contains the full markup: header, landing section, features, about, courses, enroll cards, footer, login/signup modals, etc.
-   **styles.css**: All styling rules, animations, responsive layouts, flip card logic, smooth scroll, etc.
-   **images/**: Contains all images used in the project (logos, background, course thumbnails).

---

## 🎯 Features & Highlights

-   **Landing Page** with hero message, call-to-action button.
-   **Smooth scroll** from “Get Started” to the “Courses” section (via CSS `scroll-behavior: smooth`).
-   **Flip cards** for courses — front shows image + text, back shows “Enroll Now” button.
-   **Responsive design** for desktop, tablet, and mobile screen sizes.
-   **Login / Signup modals** implemented with CSS toggles (checkbox hack) — no JavaScript.
-   **Gradient animations** on headers, buttons, and elements to add polish and visual flair.
-   **Sticky header** that remains visible when scrolling.

---

## 🛠 Usage / Run Locally

1.  **Clone the repository**

    ```bash
    git clone https://github.com/rahul17singla/strike-hackathon.git
    cd strike-hackathon
    ```

2.  **Open in browser**

    Simply open index.html in a browser (Chrome, Firefox, Edge, etc.).
    Or serve via a local HTTP server:

        ```
        # Python 3
        python3 -m http.server 8000
        # Then visit http://localhost:8000
        ```

3.  **Modify / extend**

    Add images under images/ and reference them in HTML or CSS.

    Tweak styles in styles.css — colors, animations, layout.

    Add or remove course cards by copying the flip-card HTML structure.

    Update the “Enroll Now” buttons, links, and modals as needed.
