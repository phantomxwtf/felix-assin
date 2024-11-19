# Void IX Landing Page
vug/csc/22/6904
taiwo caleb toluwase 
A modern, responsive landing page for Void IX Elite Strategies featuring dark theme aesthetics, animated elements, and an integrated video modal. Built with Tailwind CSS, Bootstrap, and jQuery.

## 🌟 Features

### Visual Design
- Dark theme with purple accents
- Gradient backgrounds
- Custom Google Fonts (Cinzel and Cormorant Garamond)
- Responsive design for all screen sizes
- Smooth hover animations
- Font Awesome icons integration

### Components
1. **Navigation Bar**
   - Sticky header
   - Responsive mobile menu
   - Smooth scroll navigation

2. **Hero Section**
   - Large headline and subtext
   - Call-to-action button with video modal

3. **Features Section**
   - Three-column grid layout
   - Animated hover effects
   - Icon-based feature cards

4. **Testimonials**
   - Bootstrap carousel
   - Auto-playing testimonials
   - Navigation controls

5. **Footer**
   - Social media links
   - Copyright information

### Interactive Elements
- Local video modal with custom controls
- Hover animations on all interactive elements
- Smooth scrolling navigation
- Mobile-responsive hamburger menu

## 🚀 Quick Start

### Prerequisites
- Web server (local or hosted)
- Text editor
- Basic understanding of HTML/CSS/JavaScript

### Installation

1. **Clone or download the repository**
   ```bash
   git clone [repository-url]
   ```

2. **Project Structure**
   Create the following structure:
   ```
   void-ix/
   ├── index.html
   ├── videos/
   │   └── [your-video-file]
   └── README.md
   ```

3. **Add Your Video**
   - Place your video file in the `videos` folder
   - Supported formats: MP4, WebM
   - Update the video source in `index.html`:
   ```html
   <video id="localVideo" controls>
     <source src="videos/your-video-file.mp4" type="video/mp4">
     <source src="videos/your-video-file.webm" type="video/webm">
   </video>
   ```

4. **Running Locally**
   - Use a local web server (e.g., Live Server in VS Code)
   - Open `index.html` through the web server
   - Don't open the file directly in a browser as video playback might not work

## 🎨 Customization

### Colors
The site uses a custom color scheme that can be modified:
- Primary: Purple (#9b59b6)
- Dark backgrounds: Black and various gray shades
- Text: White and light gray
- Accents: Purple variations

To change colors:
1. Modify Tailwind classes in HTML
2. Update hover effect colors in CSS

### Fonts
To change fonts:
1. Update Google Fonts link in `<head>`
2. Modify font-family classes:
   ```css
   .font-cinzel {
     font-family: 'Your-Font', serif;
   }
   .font-cormorant {
     font-family: 'Your-Other-Font', serif;
   }
   ```

### Content
Key areas to customize:
- Navigation menu items
- Hero section text and CTA
- Feature cards content
- Testimonials
- Social media links
- Footer text

### Video Modal
Customize video player:
1. Update video sources
2. Modify modal styling in CSS
3. Adjust autoplay and control settings
4. Change modal animations in JavaScript

## 📱 Responsive Design

The page is fully responsive with breakpoints:
- Mobile: < 640px
- Tablet: 640px - 1024px
- Desktop: > 1024px

## 🛠 Dependencies

- Tailwind CSS (via CDN)
- Bootstrap 5.3.0
- Font Awesome 6.5.1
- jQuery 3.6.0
- Google Fonts (Cinzel, Cormorant Garamond)

## ⚠️ Important Notes

1. **Video Hosting**
   - Keep video files relatively small for better performance
   - Consider using compressed versions for mobile
   - Ensure proper video codec support

2. **Browser Support**
   - Tested on latest versions of Chrome, Firefox, Safari, and Edge
   - Video playback requires modern browser support
   - Fallback message included for unsupported browsers

3. **Performance**
   - Optimize images and video files
   - Consider lazy loading for images
   - Minimize custom CSS/JS where possible

## 📄 License

Copyright © 2024 Void IX. All rights reserved.

## 🤝 Contributing

To contribute to this project:
1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## 🐛 Known Issues

1. Video autoplay may be blocked on some mobile browsers
2. Custom video controls styling varies across browsers

## 💡 Support

For support or questions, contact: [Your Contact Information]

## 🔄 Updates

Check back regularly for updates and new features.
