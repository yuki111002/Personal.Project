**Project Title:** Design and Development of a Promotional Website for a privately owned land and pool in Igbobolo<br>
**Designer:** Nathaniel S. Yu BSIT-3B<br>

**Short Overview of the Project:** This project promotes Igbobolo which is a privately owned land. This website presents what Igbobolo has to offer which are an adventure hike and a refreshing pool and the feeling of being home or comforted, it also contains a gallery with different contents which can be crucial in promoting Igbobolo. This website has a simple layout but has modern touches here and there producing a clean and modern layout and easy to navigate so visitors can seamlessly navigate through the website and learn more about Igbobolo and what it has to offer.

**Framework Used:** 
Html5 - Structure of the webpages.
TailwindCSS - Tailwind CSS for a fully responsive, utility-first design.
Vanilla Javascript - Vanilla JavaScript for scroll reveal animations, modal toggling, and infinite gallery scrolling.
Google Sheets/Apps Script - Google Apps Script linked to Google Sheets for a serverless database and automated email notifications.
Google Fonts - Playfair Display, Inter, and Dancing Script

**Use of AI Tool:** Gemini
**How it is used:** Acted as a pair-programmer and technical consultant to generate responsive frontend code (HTML/Tailwind CSS), engineer custom CSS animations, and develop a serverless backend integration for data collection.

## 1. Architectural Foundation & Responsiveness
* **AI Tool Used:** Gemini
* **Prompts:**
* "Create a basic portfolio structure for a private mountain resort called Igbobolo Sanctuary using Tailwind CSS and Flowbite."
* "Implement a modular frontend structure for header and footer includes to improve component reusability."
* "Same issue, the nav bar getting pushed back has appeared again... fix the mobile resolution issues so the UI stays consistent."
* **How it is used:** I used the AI to establish a scalable multi-page HTML5 framework. It provided the initial responsive skeleton, engineered a custom sticky navigation system that remains functional across mobile and desktop, and debugged complex z-index and positioning conflicts caused by massive image content.

## 2. Backend & Functional Integration
* **AI Tool Used:** Gemini
* **Prompts:**
* "The button should display the message saying inquiry sent or something without having to type in the fields."
* "Same issue, the nav bar getting pushed back has appeared again... fix the mobile resolution issues so the UI stays consistent."
* **How it is used:** I used the AI to bridge the gap between a static frontend and a functional backend. It generated a custom Google Apps Script to act as a serverless database and engineered the JavaScript fetch logic to handle data transmission. This allowed for real-world inquiry collection and automated email notifications without a traditional web server.

## 3. Complex Grid & Layout Architecture
* **AI Tool Used:** Gemini
* **Prompts:**
* "Add a gallery section that has one big picture covered with smaller ones, implementing this into the existing Home page code."
* "I mean use that as inspiration the gallery page is another separate new page... add 9 more lines of images."
* **How it is used:** I utilized the AI to handle high-level CSS Grid logic. It translated a visual "masonry" concept into responsive code that interlocks images of varying sizes. It also managed the transition of this complex grid from a single section into a standalone, multi-page architecture while maintaining grid-flow-dense logic for seamless layouts.

## 4. Styling & Motion Design
* **AI Tool Used:** Gemini
* **Prompts:**
* "Revise the gallery to make the images wavy... Make them move continuously where the first line goes to the right, the second to the left, alternating, while adding shadows for depth."
* "Center all titles, remove the line below each title, also make the background white... make the images like not straight."
* **How it is used:** I used the AI to engineer advanced, performance-focused motion. It generated custom @keyframes for infinite scrolling and applied alternating nth-child transformations to create a deep, organic "wavy" effect. It also acted as a design consultant to clean up the UI, ensuring the typography and background stayed minimalist and professional.

## 5. Custom Asset & Component Engineering
* **AI Tool Used:** Gemini
* **Prompts:**
* "Create a back-to-top button fixed at the bottom right... Use the silhouette of a mountain to act like the arrow pointer... not too arrow-y."
* "Implement Option 1 (Minimalist Peak)."
* **How it is used:** I used the AI as a technical illustrator to write raw SVG path data. Instead of using generic icons, the AI developed a bespoke minimalist mountain peak that functions as a navigation element. It then wrote the Intersection Observer logic to ensure the button only appears when the user has scrolled a certain depth.