# Om Kumar - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing my skills, projects, and achievements as a Computer Science Engineering student and aspiring Software Engineer.

## 🌟 Features

### Design & User Experience
- **Modern UI/UX**: Clean, professional design with elegant typography and smooth animations
- **Responsive Design**: Fully responsive layout that works perfectly on all devices
- **Light/Dark Theme**: Toggle between light and dark themes with persistent preference storage
- **Smooth Animations**: CSS animations and JavaScript-powered scroll animations
- **Professional Layout**: Well-organized sections with soft color transitions and card-based design

### Sections
1. **Home Section**: Hero section with name, title, and call-to-action buttons
2. **About Section**: Personal bio, education, and interests
3. **Skills Section**: Technical skills organized by category (Programming, Frontend, Backend, Tools)
4. **Projects Section**: Featured projects with descriptions, technologies, and links
5. **Achievements Section**: Certifications, internships, and academic achievements
6. **Contact Section**: Contact form and contact information with social media links

### Technical Features
- **Mobile-First Design**: Responsive navigation with hamburger menu
- **Smooth Scrolling**: Navigation with smooth scroll to sections
- **Scroll Animations**: Intersection Observer API for scroll-triggered animations
- **Form Validation**: Contact form with client-side validation
- **Performance Optimized**: Throttled scroll events and optimized animations
- **Accessibility**: Semantic HTML and keyboard navigation support

## 🚀 Technologies Used

- **HTML5**: Semantic markup and modern HTML features
- **CSS3**: CSS Grid, Flexbox, CSS Variables, and advanced animations
- **JavaScript (ES6+)**: Modern JavaScript with modular functions
- **Font Awesome**: Icons for enhanced visual appeal
- **Google Fonts**: Inter and Poppins font families

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
├── netlify.toml        # Netlify deployment configuration
└── resume/             # Resume folder
    ├── Om_Kumar_Resume.pdf  # Main resume file
    └── README.md            # Resume folder documentation
```

## 🛠️ Setup Instructions

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. **Clone or Download**
   ```bash
   # If using Git
   git clone <repository-url>
   cd portfolio
   
   # Or simply download and extract the ZIP file
   ```

2. **Add Your Resume**
   - Place your resume PDF file in the `resume/` folder
   - Rename it to `Om_Kumar_Resume.pdf` or update the path in `script.js`
   - See `resume/README.md` for detailed instructions

3. **Customize Content**
   - Edit `index.html` to update personal information
   - Modify `styles.css` to change colors, fonts, or layout
   - Update `script.js` for custom functionality

4. **Open in Browser**
   - Double-click `index.html` or open with your preferred browser
   - Or use a local server for development

### Local Development Server (Optional)

For better development experience, you can use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have it installed)
npx serve .

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 🎨 Customization

### Colors and Theme
The website uses CSS variables for easy customization. Edit the `:root` section in `styles.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --secondary-color: #7c3aed;    /* Secondary color */
    --accent-color: #06b6d4;       /* Accent color */
    /* ... other variables */
}
```

### Content Updates
- **Personal Information**: Update name, title, bio, and contact details in `index.html`
- **Projects**: Modify project cards with your own projects and descriptions
- **Skills**: Add or remove skills in the skills section
- **Achievements**: Update certifications and achievements

### Adding New Sections
To add new sections, follow the existing pattern in `index.html` and add corresponding styles in `styles.css`.

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📧 Contact Form Integration

The contact form is currently set up with simulated functionality. To integrate with a real backend:

1. **EmailJS Integration** (Recommended for static sites):
   ```javascript
   // Add EmailJS script to HTML
   <script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
   
   // Initialize EmailJS in script.js
   emailjs.init("YOUR_USER_ID");
   
   // Update handleContactForm function
   ```

2. **Backend Integration**:
   - Replace the form submission logic in `handleContactForm()`
   - Add your API endpoint and authentication

## 🚀 Deployment

### Netlify (Recommended)
1. Push your code to GitHub
2. Connect your repository to Netlify
3. Deploy automatically on every push

### GitHub Pages
1. Push your code to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main` or `master`)

### Other Platforms
- **Vercel**: Great for static sites with automatic deployments
- **Firebase Hosting**: Google's hosting solution
- **AWS S3 + CloudFront**: Enterprise-grade hosting

## 🔧 Performance Optimization

The website includes several performance optimizations:

- **Throttled Scroll Events**: Prevents excessive function calls during scrolling
- **Intersection Observer**: Efficient scroll-triggered animations
- **CSS Transitions**: Hardware-accelerated animations
- **Optimized Images**: Placeholder icons instead of heavy images
- **Minimal Dependencies**: Only essential external libraries

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📞 Contact

- **Email**: omkumarom527@gmail.com
- **GitHub**: [github.com/omkumar](https://github.com/omkumar)
- **LinkedIn**: [linkedin.com/in/omkumar](https://linkedin.com/in/omkumar)

## 🙏 Acknowledgments

- Font Awesome for the beautiful icons
- Google Fonts for the typography
- The open-source community for inspiration and best practices

---

**Built with ❤️ by Om Kumar**

*Computer Science Engineering Student | Software Engineer | Java & React.js Developer*
