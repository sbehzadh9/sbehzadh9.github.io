# Behzad's Portfolio Website

A modern, responsive portfolio website inspired by Yogesh Gajjar's design. Built with HTML, CSS, and JavaScript, featuring smooth animations, interactive elements, and a clean, professional design.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean design with smooth animations and hover effects
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Scroll-triggered animations
  - Mobile-friendly hamburger menu
  - Contact form with validation
  - Typing effect on hero title
  - Parallax background effects
- **Sections Included**:
  - Hero section with animated background
  - About section
  - Experience timeline
  - Education
  - Projects showcase
  - Skills display
  - Contact form
- **Performance Optimized**: Fast loading with minimal dependencies

## File Structure

```
behzad/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization Guide

### 1. Personal Information

Edit the `index.html` file to update your personal information:

#### Hero Section
```html
<h1 class="hero-title">Your Name</h1>
<h2 class="hero-subtitle">Your Title | Your Skills | Your Focus</h2>
```

#### About Section
Update the about text with your personal story and background.

#### Contact Information
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, State</span>
</div>
```

### 2. Experience Section

Replace the experience items with your own:

```html
<div class="timeline-item">
    <div class="timeline-content">
        <h3 class="job-title">Your Job Title</h3>
        <h4 class="company">Company Name</h4>
        <p class="job-description">
            Your job description and responsibilities.
        </p>
        <div class="job-tech">
            <strong>Languages:</strong> Your languages<br>
            <strong>Technologies:</strong> Your technologies
        </div>
    </div>
</div>
```

### 3. Education Section

Update with your educational background:

```html
<div class="education-item">
    <h3 class="degree">Your Degree</h3>
    <h4 class="institution">University Name</h4>
    <p class="duration">Year - Year</p>
    <p class="gpa">GPA: X.XX/X.XX</p>
    <div class="coursework">
        <strong>Coursework:</strong>
        <ul>
            <li>Course 1</li>
            <li>Course 2</li>
        </ul>
    </div>
</div>
```

### 4. Projects Section

Add your own projects:

```html
<div class="project-card">
    <div class="project-content">
        <h3 class="project-title">Project Name</h3>
        <p class="project-description">
            Project description and what you accomplished.
        </p>
        <div class="project-tech">
            <strong>Stack:</strong> Technologies used
        </div>
        <a href="#" class="project-link">View Project</a>
    </div>
</div>
```

### 5. Skills Section

Update the skills with your expertise:

```html
<div class="skills-category">
    <h3>Category Name</h3>
    <div class="skills-list">
        <span class="skill-tag">Skill 1</span>
        <span class="skill-tag">Skill 2</span>
    </div>
</div>
```

### 6. Color Scheme

To change the color scheme, edit the CSS variables in `styles.css`:

```css
/* Primary colors */
--primary-color: #4299e1;
--secondary-color: #667eea;
--accent-color: #764ba2;

/* Text colors */
--text-primary: #2d3748;
--text-secondary: #4a5568;
--text-muted: #718096;
```

### 7. Social Links

Update the social media links in the contact section:

```html
<div class="social-links">
    <a href="https://github.com/yourusername" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="https://linkedin.com/in/yourusername" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://twitter.com/yourusername" class="social-link">
        <i class="fab fa-twitter"></i>
    </a>
</div>
```

## Deployment

### GitHub Pages (Recommended)

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify

1. Drag and drop the folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly
3. You can set up a custom domain if needed

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts to deploy

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

1. **Optimize Images**: Use WebP format and compress images
2. **Minify CSS/JS**: Use tools like UglifyJS and CSSNano
3. **Enable Gzip**: Configure your server to serve compressed files
4. **Use CDN**: Consider using a CDN for faster loading

## Customization Examples

### Adding a Blog Section

```html
<section id="blog" class="section">
    <div class="container">
        <h2 class="section-title">Blog</h2>
        <div class="blog-grid">
            <article class="blog-card">
                <h3>Blog Post Title</h3>
                <p>Blog post excerpt...</p>
                <a href="#" class="read-more">Read More</a>
            </article>
        </div>
    </div>
</section>
```

### Adding a Resume Download Button

```html
<div class="hero-buttons">
    <a href="#about" class="btn btn-primary">Learn More</a>
    <a href="path/to/resume.pdf" class="btn btn-secondary" download>Download Resume</a>
</div>
```

## Troubleshooting

### Common Issues

1. **Images not loading**: Check file paths and ensure images are in the correct directory
2. **Fonts not loading**: Verify Google Fonts link is working
3. **Animations not working**: Check if JavaScript is enabled
4. **Mobile menu not working**: Ensure all JavaScript files are loaded

### Performance Issues

1. **Slow loading**: Optimize images and minify CSS/JS
2. **Animations lagging**: Reduce animation complexity on mobile devices
3. **Large file sizes**: Use image compression and remove unused CSS


## Credits

- Fonts: [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)
- Icons: [Font Awesome](https://fontawesome.com/)
- Design inspiration: Yogesh Gajjar's portfolio

## Support

If you need help customizing or deploying your portfolio, feel free to:

1. Check the documentation above
2. Look at the code comments for guidance
3. Test changes locally before deploying

---

**Happy coding! 🚀** 
