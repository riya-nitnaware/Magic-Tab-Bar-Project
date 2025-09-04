# 🌟 Iconic Magic Tab Bar

A **modern, animated tab navigation bar** built completely with **HTML and CSS**.  
The Magic Tab Bar provides smooth glowing effects, hover animations, and a clean layout that makes switching between sections feel interactive and professional. This project is ideal for portfolios, web apps, or any website where a unique navigation experience is needed.



## ✨ Key Highlights
- **Pure HTML & CSS only** – no JavaScript, no external images.
- **Five navigation items**: Home, Search, Notification, Favorites, and Profile.
- **Glowing selector effect** – an animated circular highlight that smoothly moves to the active tab.
- **Custom icons with CSS** – each tab’s icon (house, search lens, bell, heart, user) is drawn using gradients, borders, and pseudo-elements.
- **Smooth hover transitions** – glowing text and icon effects when hovering.
- **Responsive-ready** – works neatly on both landscape and portrait orientations.



## 🛠️ Technologies Used
- **HTML5** → for the structure and tab selection (radio inputs + labels).  
- **CSS3** → for animations, gradients, hover effects, glowing highlights, and custom icons.  



## 📂 Project Files
```

Magic-Tab-Bar/
│── index.html   # HTML file with tab bar structure
│── style.css    # CSS file for styling and animations
└── README.md    # Documentation



## 📖 How It Works
1. Each tab is created using a **hidden radio button** paired with a clickable **label**.  
   - Only one tab can be active at a time because all radios share the same `name`.  
   - The first tab (Home) is selected by default.  

2. The **`.selector` element** is a circular glowing highlight that moves under the active tab.  
   - CSS transitions make the movement smooth and add a glowing shadow effect.  
   - Different colors are applied for each active tab using the `--sel` CSS variable.  

3. **Icons are pure CSS shapes**, built with gradients, borders, and pseudo-elements (`::before`, `::after`).  
   - Example: The search tab uses a circle with a small rectangle rotated to look like a magnifying glass handle.  

4. Hovering over a tab increases brightness and shows a soft glow around the text and icon.  


## ▶️ Usage Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Magic-Tab-Bar.git
````

2. Open the project folder.
3. Run the `index.html` file in any modern browser.
4. Click or hover on the tabs to see the glowing transitions in action.

---

## 📱 Tabs Included

* 🏠 **Home** – represented by a house icon.
* 🔍 **Search** – magnifying glass icon.
* 🔔 **Notification** – bell icon.
* ❤️ **Favorites** – heart icon.
* 👤 **Profile** – user avatar icon.



## 🌟 Demo Preview

The navigation bar has a dark background with a glowing selector spotlight that follows the active tab.
Each tab icon glows in its own unique color:

* Home → Blue glow
* Search → Orange glow
* Notification → Green glow
* Favorites → Pink glow
* Profile → Purple glow



## 🔮 Future Enhancements

* Make the tab bar fully **mobile-responsive** with smaller layouts.
* Add **JavaScript logic** to dynamically load content for each tab.
* Support **custom themes** with different color palettes.
* Option to use **SVG or Font Awesome icons** for more variety.



## 🧑‍💻 Author

Developed with ❤️ and creativity by [Your Name](https://github.com/your-username).



## 📜 License

This project is released under the **MIT License**.
You are free to use, modify, and share it with proper attribution.






Do you also want me to **add a GitHub Pages live demo setup section** so that visitors can preview your tab bar online without downloading?
```
