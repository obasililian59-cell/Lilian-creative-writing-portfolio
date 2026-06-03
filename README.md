# Lilian-creative-writing-portfolio

A responsive web portfolio showcasing a curated collection of fiction writing projects. This site serves as a central hub for published stories, featuring synopses, genre classifications, and direct links to external publishing platforms.

📌 Project Overview

This Creative Portfolio is a static website built with HTML and CSS. It presents selected fiction works in a structured and visually consistent format, highlighting storytelling strengths and published pieces.

The project demonstrates:

- Semantic HTML structure
- Component-based layout design
- Flexbox for responsive arrangement
- Styled navigation and interactive elements
- Consistent visual branding

🛠 Technologies Used
- HTML5  
- CSS3 (Flexbox, pseudo-classes, selectors)

🧱 Structure

HTML Highlights
- `header` and `nav` for top-level navigation
- Internal anchor links (`#about-me`, `#writing-profile`, `#work-samples`) for smooth page navigation
- `section` and `article` elements for semantic grouping
- Reusable `.Book` component for each writing sample
- `dl`, `dt`, and `dd` for structured synopsis presentation
- External links to published works
- Footer with return navigation and copyright

Each writing sample follows a consistent structure:
- Title  
- Cover Image  
- Author & Genre  
- Synopsis  
- External “Read here” link

🎨 CSS Highlights
- Flexbox layout for `.Book-container`:
  ```css
  .Book-container {
      display: flex;
      flex-flow: row wrap;
  }
  ```
  This allows book cards to wrap responsively across screen sizes.

- Reusable card styling for `.Book`
- Custom hover states for navigation and call-to-action buttons
- Consistent color palette (Teal & Coral tones)
- Border radius and box shadows for depth
- Styled list markers using `li::marker`
- Selective image styling using `img:not(.logo)`
- Visual emphasis using transforms (`transform: skew(2deg)` on sections)


📱 Responsiveness
The portfolio uses:

- Flexible widths (`width: 100%`)
- Flexbox wrapping
- Max-width constraints on book cards

These ensure the layout adapts naturally across devices without breaking structure.

🎯 Purpose
This project serves as:
- A professional writing portfolio
- A showcase of published fiction
- A demonstration of frontend layout and styling skills
- A reusable template for future creative expansions

👩🏽‍💻 Author
Obasi Lilian Uchechi
Frontend Developer (in transition) & Fiction Writer  
Based in Imo State, Nigeria

🔗 Navigation
- `index.html` – Main developer portfolio  
- `about me.html` – Personal background  

📜 License
All writing content is the intellectual property of Obasi Lilian.  
All rights reserved © 2026
