# Static HTML/CSS Version of Dezinerdot Landing Page

This is a pure HTML and CSS version of the UX/UI Design mentorship landing page, converted from the original React + Tailwind implementation.

## 📁 Files

- **index.html** - Main HTML file with all page content
- **styles.css** - Complete CSS file with all styles and animations
- **client/public/** - Directory containing images and assets

## 🚀 How to Use

### Option 1: Direct File Opening
Simply open `index.html` in any modern web browser:
```bash
open index.html
# or double-click the file
```

### Option 2: Local Web Server (Recommended)
For proper asset loading, use a local web server:

**Using Python:**
```bash
python -m http.server 8000
# Then visit http://localhost:8000
```

**Using Node.js (http-server):**
```bash
npx http-server -p 8000
# Then visit http://localhost:8000
```

**Using VS Code Live Server:**
1. Install the "Live Server" extension
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 📂 Required Assets

Make sure these images exist in the `client/public/images/` directory:
- `logo.png` - Dezinerdot logo
- `hero-student.png` - Hero section image
- `mentor-ranga.jpeg` - Mentor profile image

The favicon should be at `client/public/favicon.png`

## ✨ Features Included

### Sections
- ✅ Fixed Navigation Bar with smooth scroll links
- ✅ Hero Section with call-to-action
- ✅ Pain Points Section (Why You Are Stuck)
- ✅ Curriculum Timeline (6-Step Roadmap)
- ✅ Mentor Section (About Ranga)
- ✅ Testimonials/Success Stories
- ✅ Final CTA Section
- ✅ Footer with social links

### Interactions
- ✅ Smooth scroll navigation
- ✅ Scroll-triggered reveal animations
- ✅ Hover effects on cards and buttons
- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Call button with phone link integration

## 🎨 Design Features

- Custom CSS animations (fade-in, slide-in, scale)
- CSS-only implementation (no JavaScript frameworks)
- Responsive grid layouts
- Google Fonts integration (Inter & Plus Jakarta Sans)
- Color scheme matching original design
- Shadow and blur effects
- Gradient backgrounds

## 📱 Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## 🔧 Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
  --primary: hsl(43, 100%, 50%); /* Change primary color */
  --background: hsl(0, 0%, 100%); /* Background color */
  /* ... more variables */
}
```

### Content
Edit text directly in `index.html` - all content is in plain HTML.

### Images
Replace images in `client/public/images/` directory with your own.

## 📞 Contact Information

The phone number (+91 9703448442) is used throughout the page in call-to-action buttons. Update it in `index.html` if needed.

## 📝 Notes

- This is a static version without React/Tailwind dependencies
- All animations are CSS-based for smooth performance
- The design is fully responsive and mobile-friendly
- Minimal JavaScript used (only for scroll behavior and reveal animations)

## 🆚 Differences from React Version

- No Framer Motion (replaced with CSS animations)
- No Tailwind CSS classes (converted to custom CSS)
- No React components (pure HTML)
- Lightweight and fast loading
- Easy to host on any static web server

---

**Original React Version:** Uses Vite + React + Tailwind + shadcn + Framer Motion  
**Static Version:** Pure HTML + CSS with minimal JavaScript
