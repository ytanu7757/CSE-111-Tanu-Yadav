# Portfolio - Interactive Team Portfolio Website

A modern, responsive portfolio website showcasing the work of five talented individuals. Built with HTML5, CSS3, and vanilla JavaScript, featuring smooth animations, interactive elements, and accessibility compliance.

## 🚀 Features

### ✨ Interactive Elements
- **Smooth Scrolling Navigation** - Seamless navigation between sections
- **Dynamic Loading Animation** - Professional loading screen on page load
- **Hover Effects** - Interactive project cards and UI elements
- **Modal Windows** - Detailed project information in elegant modals
- **Responsive Design** - Optimized for all device sizes
- **Accessibility Compliant** - WCAG guidelines followed

### 🎨 Design Features
- **Modern Gradient Backgrounds** - Eye-catching visual appeal
- **Floating Card Animations** - Engaging hero section visuals
- **Skill Tag Animations** - Interactive skill displays
- **Profile Image Shimmer Effects** - Professional profile presentations
- **Form Validation** - User-friendly contact form

### ⚡ Performance Optimizations
- **Lazy Loading** - Efficient resource loading
- **Debounced Scroll Events** - Smooth performance
- **CSS Animations** - Hardware-accelerated transitions
- **Minified Assets** - Fast loading times
- **Progressive Enhancement** - Works without JavaScript

## 👥 Team Members Featured

### 1. Shradul Sharma - Tech Enthusiast & Aspiring Developer
- **Skills**: C Programming, C++, Problem Solving, App Development, Cybersecurity, Open Source
- **Location**: Ambala, Haryana
- **Projects**: C++ Learning Projects, Cybersecurity Learning, Open Source Contributions

### 2. Ritesh Raj - Motivated Learner & Academic Achiever
- **Skills**: Communication, Reading, Sports, Technology, Photography, Coding
- **Background**: Mount Litera Zee School & Green Valley International School, Muzaffarpur
- **Projects**: Academic Excellence, Creative Photography, Learning & Development

### 3. Harshwardhan - Motivated Learner & Creative Thinker
- **Skills**: Communication, Creative Thinking, Sports, Drawing, Music, Adaptability
- **Background**: DAV Bakhri, Muzaffarpur
- **Projects**: Academic Foundation, Creative Arts, Personal Growth

### 4. Tanu Yadav - Enthusiastic Learner & Creative Individual
- **Skills**: Quick Learning, Positive Attitude, Drawing, Music, Fitness, Communication
- **Location**: Varanasi, Uttar Pradesh
- **Projects**: Academic Excellence, Fitness & Wellness, Social & Creative Skills

### 5. George Chacko - First-Year Tech Student & Aspiring Developer
- **Skills**: Technology, Engineering, Software Design, User Experience, Web Development, Learning
- **Background**: First-year student at Lovely Professional University
- **Projects**: Academic Journey at LPU, Personal Website Development, Future Development Goals

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and accessibility
- **CSS3** - Modern styling with Grid, Flexbox, and Animations
- **Vanilla JavaScript** - Interactive functionality and DOM manipulation
- **Font Awesome** - Professional icons
- **Google Fonts** - Typography (Inter font family)

## 📁 Project Structure

```
Portfolio/
├── index.html              # Main HTML file
├── css/
│   └── styles.css          # Complete stylesheet with animations
├── js/
│   └── script.js           # Interactive functionality
├── assets/
│   └── images/             # Image assets (placeholder folder)
└── README.md               # Project documentation
```

## 🚦 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional but recommended)

### Installation

1. **Clone or Download** the project files
2. **Open the project** in your preferred code editor
3. **Launch a local server** (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have live-server installed)
   live-server
   
   # Using PHP
   php -S localhost:8000
   ```
4. **Open your browser** and navigate to `http://localhost:8000`

### Direct File Access
Alternatively, you can open `index.html` directly in your browser, though some features may work better with a local server.

## 🎨 Customization Guide

### Adding New Team Members

1. **Update HTML**: Add a new section in `index.html`:
```html
<section id="individual-6" class="individual-section">
    <!-- Copy structure from existing individual sections -->
</section>
```

2. **Update Navigation**: Add navigation link:
```html
<li role="none"><a href="#individual-6" role="menuitem" class="nav-link">NewName</a></li>
```

3. **Update JavaScript**: Add project data in `script.js`:
```javascript
const projectData = {
    // Add new project entries with incremented IDs
    16: {
        title: "New Project",
        description: "Project description...",
        tech: ["Tech1", "Tech2"],
        liveDemo: "#",
        github: "#"
    }
};
```

### Styling Customization

1. **Colors**: Update CSS custom properties in `:root`:
```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    /* Update other color variables */
}
```

2. **Fonts**: Replace Google Fonts link in HTML and update CSS:
```css
--font-family: 'YourFont', system-ui, sans-serif;
```

3. **Animations**: Modify animation durations and effects in CSS:
```css
--transition-normal: 0.3s ease-in-out; /* Adjust timing */
```

### Adding Real Images

1. Place images in the `assets/images/` folder
2. Update the HTML image placeholders:
```html
<div class="profile-image">
    <img src="assets/images/profile-1.jpg" alt="Alex Chen">
</div>
```
3. Update project images in the JavaScript modal data

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## ♿ Accessibility Features

- Semantic HTML structure
- ARIA labels and roles
- Keyboard navigation support
- Screen reader compatibility
- High contrast mode support
- Reduced motion preferences respected
- Focus indicators for keyboard users

## 🔧 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 📊 Performance Features

- **Lazy Loading**: Images and content load as needed
- **Debounced Events**: Scroll events optimized for performance
- **CSS Hardware Acceleration**: Smooth animations
- **Intersection Observer**: Efficient scroll-based animations
- **Performance Monitoring**: Built-in performance tracking

## 🚀 Deployment

### GitHub Pages
1. Upload files to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop the project folder to Netlify
2. Your site will be automatically deployed

### Traditional Web Hosting
1. Upload all files to your web server
2. Ensure the main file is named `index.html`

## 🤝 Contributing

1. Fork the project
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📝 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## 🐛 Troubleshooting

### Common Issues

**JavaScript not working?**
- Check browser console for errors
- Ensure you're using a modern browser
- Try running from a local server instead of file://

**Animations not smooth?**
- Check if "Reduce Motion" is enabled in your system preferences
- Ensure hardware acceleration is enabled in your browser

**Mobile layout issues?**
- Clear browser cache and refresh
- Test in browser developer tools device mode

## 📞 Support

For questions or issues:
1. Check the troubleshooting section above
2. Review the code comments for implementation details
3. Test in different browsers to isolate issues

## 🎯 Future Enhancements

- [ ] Add dark mode toggle
- [ ] Implement email functionality for contact form
- [ ] Add more animation presets
- [ ] Create CMS integration options
- [ ] Add blog section capability
- [ ] Implement progressive web app features

---

**Made with ❤️ for showcasing amazing talent**