# Netflix-Clone
A frontend project replicating the Netflix landing page, built to practice modern CSS layouts, element positioning, and professional UI structure. This project serves as a foundation for a full-featured web application as I progress in my frontend development journey.
## 📌 Project Overview
This project was developed to master the art of replicating complex, professional UIs. The primary goal was to achieve a pixel-perfect design and understand how to manage multiple sections with overlapping elements (like videos inside TV frames) using clean, maintainable code.
## 🛠️ Tech Stack
HTML5: Semantic markup to ensure a well-structured document.
CSS3: Flexbox for layout alignment, absolute positioning for overlays, and custom font integration via Google Fonts.
SVG Integration: Using scalable vector graphics for icons and logos to maintain clarity at any resolution.
## ✨ Key Features (Current)
Hero Section: High-impact landing area with custom background blending.
Video Overlays: Successfully implemented absolute positioning to embed functional video players within static device frames (TV and Tablet images).
Semantic Structure: Clean use of header, footer, and section tags for better code readability.
FAQ Architecture: A styled Frequently Asked Questions section prepared for future logic implementation.
## 🧠 Technical Challenges & Solutions
Layering with Z-Index: One of the main challenges was ensuring that the video sits behind the TV frame but stays clickable/visible. I solved this by managing a z-index stack where the transparent TV PNG sits on top, and the video element sits precisely beneath it.
Flexbox Spacing: Managing the "zebra-striping" (alternating text and images) required a deep dive into Flexbox alignment to ensure consistent padding and margins across the entire page.
## 🗺️ Roadmap (Current & Upcoming Goals)
I am actively developing this project. My next steps include:

Media Queries & Responsive Design: Implementing breakpoints to ensure the layout is fully functional on mobile and tablet devices.

JavaScript Interactivity: Adding logic to the FAQ section to create a functional accordion.

TMDB API Integration: Building a "Browse" page that fetches real-time movie data.

Data Persistence: Using LocalStorage to allow users to save movies to a "My List" section.

✍️ Author
Nishtha Gupta
