# Project Report: Advanced CSS (Flexbox & Grid Layouts)
# 1. Project Summary
This project is a frontend web development assignment focused on building a user-frendly and visually clear web page using advanced CSS techniques, specifically CSS Flexbox and CSS Grid. The project combines two main concepts: a car catalog ("L-Motors Catalog") and a personal developer portfolio. The main goal was to structure web components effectively and implement modern hover effects and transitions.

# 2. Project Parts Details (All Parts)
## Part 1: L-Motors Catalog (Flexbox Implementation)
This section demonstrates the use of CSS Flexbox for alignment and spacing.

**Header & Navigation**: The top navigation bar uses display: flex; with justify-content: space-between; to separate the logo and the navigation links smoothly.

**Product Cards (#part1)**: The car catalog features three product cards (BMW, Porsche, Mercedes). The container (.card-conteiner) uses Flexbox to align the cards horizontally. Each individual card applies flex-direction: column; to align the image, title, text, and button vertically.

**Interactive Effects:** Cards feature a transform: translateY(-10px); and box-shadow transition upon hovering to create an interactive "lift" effect.

<img width="959" height="411" alt="image" src="https://github.com/user-attachments/assets/1d910a45-392b-488b-b2bb-39a1f29b42c9" />


## Part 2: Grid System Layout
This section showcases the fundamental understanding of CSS Grid areas.

**Layout Structure**: A container (.grid-conteiner) is divided using grid-template-areas into four main semantic regions: Header, Sidebar, Main content, and Footer.

This demonstrates how easily complex page structures can be built without heavily nesting HTML div tags.

<img width="941" height="374" alt="image" src="https://github.com/user-attachments/assets/78b4540e-26ff-446c-9fc2-3f8b89fd7405" />


## Part 3: Image Gallery (#part2)
The gallery section uses CSS Grid to display a collection of car brand logos (Subaru, Ford, Toyota, etc.).

**Grid Setup**: The .gallery-conteiner uses grid-template-columns: repeat(3, 1fr); to create an automatic 3-column layout.

**Animations**: Each .gallery-item has an overflow: hidden; property. When a user hovers over the image, the image scales up slightly (transform: scale(1.05);), and a semi-transparent dark caption block slides up from the bottom (transform: translateY(0);).

<img width="477" height="319" alt="image" src="https://github.com/user-attachments/assets/ddca6f64-2342-4067-93cd-fd0eb743e110" />


## Part 4: Personal Portfolio Page
The final section combines previous concepts into a standard portfolio layout.

**Structure**: The .portfolio-main uses a two-column CSS Grid (3fr 1fr) to separate the main projects area from the "About me" sidebar.

**Projects Grid**: Inside the projects area, .projects-grid utilizes grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); for a highly responsive layout that automatically wraps project cards based on screen size. Flexbox is used inside the cards to push the buttons to the bottom automatically (margin-top: auto;).

<img width="959" height="485" alt="image" src="https://github.com/user-attachments/assets/d541e354-7492-4ff5-a5de-bdbb12883b7a" />

## 4. Final Summary
The project successfully implements modern CSS. By using Flexbox, the internal alignment of navigation items and card contents is handled efficiently. By using CSS Grid, the macro-layout of the page (the 2D structures like the gallery and the sidebar-main layout) is built responsively. Interactive transitions enhance the overall user experience, resulting in a clean, modern, and structured webpage.
