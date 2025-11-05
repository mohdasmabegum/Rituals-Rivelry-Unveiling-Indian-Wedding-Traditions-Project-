#  Rituals and Rivelry - Unveiling Indian Wedding Traditions
# Interactive Map of India – Cultural Exploration Web App

This project is a **responsive and interactive web application** that showcases the cultural richness of Indian states through a dynamic map interface. Built using **HTML, CSS, and JavaScript**, it allows users to explore state-wise traditions, videos, and descriptions by hovering or clicking on regions of the map.

---

##  Project Objective

To create an engaging educational experience that highlights the **diverse wedding traditions, heritage, and cultural practices** across Indian states. Each state is mapped with precise coordinates and linked to custom content including videos, descriptions, and external resources.

---

##  Features

-  **Interactive India Map** with clickable and hoverable state regions
-  **Embedded video player** showcasing cultural highlights for each state
-  **Dynamic content card** with title, description, and external link
-  **Responsive layout** with clean design and subtle animations
-  **Lock/unlock mechanism** to control card visibility

---

##  Technologies Used

- **HTML5** – Semantic structure and image mapping
- **CSS3** – Styling, layout, and responsive design
- **JavaScript** – DOM manipulation, event handling, and dynamic content rendering

---

##  File Structure


---

##  How It Works

- The `<map>` element defines clickable regions using `area` tags with **polygon coordinates** for each state.
- On **hover**, a tooltip card appears showing the state's name and description.
- On **click**, the card locks in place and plays a **state-specific video**.
- The card includes a **close button** to hide the content and reset the view.

---

##  Example Interaction

```html
<area shape="poly" coords="..." 
  href="jammu and kashmir.html" 
  title="Jammu & Kashmir" 
  alt="Jammu & Kashmir" 
  onmouseover="showCard(event, 'Jammu & Kashmir', 'Explore the beauty of Jammu & Kashmir.', 'https://example.com/jk','videos/jammu kashmir.mp4')" 
  onclick="lockCard()">


 Contact
Created by Mohammad Asma Begum
 Email: mdasma1304@gmail.com
 LinkedIn: Asma Begum Mohammad

 License
© 2025 Mohammad Asma Begum. All rights reserved.


