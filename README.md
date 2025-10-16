# Portfolio Website - Ihimbru Zadolf Ongum

A modern, responsive one-page portfolio website showcasing my experience, skills, and projects as a Software Engineer.

## Features

- Modern and clean design with smooth animations
- Fully responsive (mobile, tablet, and desktop)
- Interactive navigation with smooth scrolling
- Project showcase with links
- Work experience timeline
- Skills and qualifications display
- Downloadable CV
- GitHub integration

## Technologies Used

- HTML5
- CSS3 (with modern features like CSS Grid, Flexbox, and animations)
- JavaScript (ES6+)
- Font Awesome icons

## Project Structure

```
my_portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # Stylesheet
├── js/
│   └── script.js      # JavaScript for interactivity
├── assets/
│   └── cv.pdf         # Your CV (to be added)
└── README.md          # This file
```

## Setup Instructions

### Adding Your CV

1. Place your CV (PDF format) in the `assets` folder
2. Name it `cv.pdf` or update the links in `index.html` if you use a different name

## How to Host on GitHub Pages

Follow these steps to host your portfolio on GitHub Pages using your GitHub profile:

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in to your account (username: zaza203)
2. Click the "+" icon in the top right corner and select "New repository"
3. **Important:** Name your repository `zaza203.github.io` (this is your username followed by `.github.io`)
4. Add a description (optional): "My personal portfolio website"
5. Set the repository to **Public**
6. Click "Create repository"

### Step 2: Initialize Git and Push Your Code

Open your terminal/command prompt in the `my_portfolio` directory and run these commands:

```bash
# Initialize git repository
git init

# Add all files to staging
git add .

# Create your first commit
git commit -m "Initial commit: Portfolio website"

# Add your GitHub repository as remote origin
git remote add origin https://github.com/zaza203/zaza203.github.io.git

# Rename branch to main (if needed)
git branch -M main

# Push your code to GitHub
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub: `https://github.com/zaza203/zaza203.github.io`
2. Click on "Settings" (gear icon)
3. Scroll down to the "Pages" section in the left sidebar
4. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click "Save"

### Step 4: Access Your Website

After a few minutes, your website will be live at:

**https://zaza203.github.io**

### Alternative: Using a Different Repository Name

If you want to use a different repository name (e.g., `portfolio`):

1. Create a repository with your chosen name (e.g., `portfolio`)
2. Follow steps 2 and 3 above, but update the remote URL:
   ```bash
   git remote add origin https://github.com/zaza203/portfolio.git
   ```
3. Your website will be accessible at: `https://zaza203.github.io/portfolio`

## Updating Your Portfolio

To make changes to your portfolio:

1. Edit the files locally
2. Commit and push changes:

```bash
git add .
git commit -m "Description of changes"
git push
```

3. Changes will be live within a few minutes

## Customization

### Updating Personal Information

Edit the `index.html` file to update:
- Your name and contact information
- Work experience
- Projects
- Skills
- Links to your projects and social media

### Changing Colors/Theme

Edit `css/style.css` and modify the CSS variables at the top of the file:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
    /* ... other variables ... */
}
```

### Adding New Sections

1. Add the HTML content in `index.html`
2. Style it in `css/style.css`
3. Add navigation link in the navbar if needed

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

This project is open source and available for personal use.

## Contact

- GitHub: [https://github.com/zaza203](https://github.com/zaza203)

---

Built with care by Ihimbru Zadolf Ongum
