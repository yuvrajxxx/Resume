# Resume Website

This project transforms a resume into a responsive HTML and CSS web page with a modern design. It features a fixed navigation bar, section-based layout, and enhanced styling to simulate a professional document with visual appeal.

## Features

1. **Sticky Navigation Bar**
   - The navigation bar remains fixed at the top of the page for easy access to different sections.

2. **Responsive Design**
   - The layout adapts to various screen sizes for an optimal viewing experience on desktops, tablets, and mobile devices.

3. **Modern Styling**
   - Uses Google Fonts and a gradient background for a professional and polished look.
   - Box shadow effect to give the resume a paper-like appearance.

4. **Section-Based Layout**
   - Clearly defined sections for Experience, Education, Projects, Skills, and Achievements.

## Technologies Used

- **HTML5**: For structuring the web page content.
- **CSS3**: For styling and layout.
- **Google Fonts**: For enhanced typography.
- **Responsive Design Techniques**: For mobile-friendly behavior.

## Folder Structure

## How to Run the Project

1. Clone or download the repository to your local machine.

2. Open the `index.html` file in any modern web browser (e.g., Chrome, Firefox, Edge).

3. To edit the design or content, open the files in a code editor like VSCode.

## Customization

### Change Content
- Open the `index.html` file.
- Locate the relevant sections (e.g., Experience, Education) and edit the content directly.

### Modify Styles
- Open the `style.css` file.
- Change the values of the CSS properties to customize colors, fonts, or layout.

## Highlights of the Code

### HTML Highlights
- Uses semantic tags like `<nav>`, `<section>`, and `<header>` for better readability and accessibility.
- Hyperlinked contact information using the `mailto:` and `tel:` protocols for quick access.

### CSS Highlights
- Utilizes `position: fixed` for the sticky navigation bar.
- Implements a gradient background and shadow effect for a polished appearance.
- Includes media queries for responsive design.

## Example Code Snippets

### Sticky Navigation Bar
```css
nav {
    position: fixed;
    top: 0;
    width: 100%;
    background: #343a40;
    z-index: 1000;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.resume-centre {
    width: 650px;
    margin: 20px auto;
    padding: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1), 0 1px 3px rgba(0, 0, 0, 0.08);
}

```
## License
This project is licensed under the MIT License. Feel free to use and modify it for your personal or professional needs.
