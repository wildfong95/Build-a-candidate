
# Employee Builder

Welcome to **Employee Builder** – the interactive tool designed to build the perfect employee by showcasing a curated list of skills straight from my resume. This project is built with flair using custom Balgin fonts and a refined color palette that gives it a unique branded look.

## Overview

Employee Builder is a multi-step interactive quiz that divides skills into three sections:
- **Step 1: Computer Skills**
- **Step 2: Power Skills**
- **Step 3: Technical Skills**

Once users have finished selecting their skills, a final message is displayed with a stylish image and a button linking directly to my portfolio.

## File Structure
employee_builder/
├── index.html         # Main HTML file that sets up the structure of the app
├── style.css          # Stylesheet for fonts, colors, layout, and design
├── script.js          # JavaScript for handling dynamic content and interactions
├── final-image.jpg    # Final image to be displayed on the closing page (replace with your own)
└── README.md          # This file!
## Customization & Styling

- **Fonts:**  
  - **Headers:** Uses **Balgin Condensed**
  - **Body Text:** Uses **Balgin**

  You can change the font weights or swap fonts by modifying the links in the `<head>` of `index.html`.

- **Colors:**  
  The design leverages a dark green background with light cream headers for contrast. The components (cards, buttons, etc.) utilize soft neutral shades and a gentle accent color for buttons. To adjust the colors, update the values in `style.css`.

- **Content:**  
  - Edit the `skills` object in `script.js` to update the skills in each category.
  - Replace `final-image.jpg` with your desired image.
  - Update the portfolio link in both `script.js` and within the final message area in `index.html` or `script.js`.

## Embedding in Adobe Portfolio

To showcase Employee Builder on your Adobe Portfolio, follow these steps:

1. **Deploy Your Project:**  
   You can host your project on GitHub Pages, CodePen, or any other web hosting service.

2. **Get the URL:**  
   For example, if you deploy on GitHub Pages, your URL might look like:  
   `https://yourusername.github.io/employee-builder/`

3. **Embed Using an Iframe in Adobe Portfolio:**  
   In Adobe Portfolio, add a custom code or embed module and insert the following code snippet:
   ```html
   <iframe src="https://yourusername.github.io/employee-builder/" width="100%" height="600" frameborder="0"></iframe>