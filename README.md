# Fragrance of the Day Randomizer

## Overview
This is a simple web-based fragrance randomizer that helps you select a fragrance based on the **season** and **occasion**. Right now, it's populated with stuff from my collection, but you could fork this and make it work for yours too. 

## Features
- Select **season** (Spring, Summer, Fall, Winter, Shoulder, Anytime)
- Select **occasion** (Work, Date Night, Going Out, Crowded Spaces, Casual Outdoor)
- Randomly generate a **Fragrance of the Day** based on your choices
- Collection is the union of my Parfumo + Fragrantica "I have" lists (81 fragrances)

## Usage
1. Open the `index.html` file in a web browser.
2. Choose the **season** and **occasion** from the dropdown menus.
3. Click the "Pick Fragrance" button.
4. The randomly selected fragrance will be displayed on the page.

## Deployment
You can host this project on:
- **GitHub Pages** (Upload the repository and enable Pages in settings)
- **Netlify** (Drag and drop the HTML file into Netlify for instant deployment)
- **Vercel** (Connect to GitHub and deploy the static site)

## Customization
- To add or remove fragrances, edit the `fragrances` array in the `<script>` section of `index.html`.
- Each fragrance object should have:
  ```javascript
  { name: "Brand | Fragrance Name", season: "Spring", occasion: "Work" }
  ```

## Future Improvements
- Convert to a standalone JavaScript file for better maintainability.
- Move to 4 seasons instead of 2, adding more occasions
- Add more detailed filtering (e.g., fragrance families, intensity levels).
- Improve UI styling with CSS frameworks like Bootstrap or Tailwind.

---
Enjoy exploring your fragrance collection with this simple randomizer!
