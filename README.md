# Landing Page

A modern, responsive landing page built from a Figma design with exact pixel-perfect implementation.

## Features

- **Pixel-perfect design**: Exactly matches the Figma design specifications
- **Responsive layout**: Works seamlessly across all device sizes
- **Modern typography**: Uses Inter font family with proper font weights
- **Interactive elements**: Smooth animations and hover effects
- **Optimized images**: High-quality images from Figma design
- **Clean code**: Well-structured HTML, CSS, and JavaScript

## Design Elements

### Colors
- Primary: #000000 (Black)
- Secondary: #828282 (Gray)
- Background: #FFFFFF (White)
- Accent: #E6E6E6 (Light Gray)
- CTA Background: #F7F7F7 (Very Light Gray)

### Typography
- Font Family: Inter
- Font Weights: 400 (Regular), 500 (Medium), 600 (Semi-Bold), 700 (Bold)
- Line Heights: 1.5 (Body), 1.2102272510528564em (Headings)
- Letter Spacing: -2% (Headings)

### Layout
- Maximum width: 1440px
- Container padding: 80px (desktop), 40px (tablet), 20px (mobile)
- Grid gaps: 32px (desktop), 24px (tablet)
- Border radius: 8px (cards), 12px (testimonials)

## Sections

1. **Navigation Bar**
   - Site name and navigation links
   - Call-to-action button

2. **Hero Section**
   - Large title and subtitle
   - Hero image
   - Primary call-to-action button

3. **Content Sections**
   - Three-column card layout
   - Image and text content
   - Section with side-by-side content and image

4. **Feature Cards**
   - Two-column feature layout
   - Images with descriptive text

5. **Testimonials**
   - Three-column testimonial cards
   - Customer quotes with avatars
   - Author information

6. **Call-to-Action Section**
   - Background color variation
   - Primary and secondary buttons

7. **Footer**
   - Three-column navigation
   - Social media icons
   - Site branding

## File Structure

```
Landing Page/
├── index.html          # Main HTML structure
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── images/             # Image assets from Figma
    ├── hero-image.png
    ├── card-image-1.png
    ├── card-image-2.png
    ├── card-image-3.png
    ├── section-image.png
    ├── feature-image-1.png
    ├── feature-image-2-5409b3.png
    ├── avatar-1.png
    ├── avatar-2.png
    └── avatar-3.png
```

## Responsive Breakpoints

- **Desktop**: 1440px and above
- **Tablet**: 1024px - 1439px
- **Mobile**: 768px - 1023px
- **Small Mobile**: Below 768px

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Getting Started

1. Clone or download the project files
2. Open `index.html` in your web browser
3. The page will load with all styles and functionality

## Customization

### Colors
Update the CSS custom properties in `styles.css` to change the color scheme:

```css
:root {
    --primary-color: #000000;
    --secondary-color: #828282;
    --background-color: #FFFFFF;
    --accent-color: #E6E6E6;
    --cta-background: #F7F7F7;
}
```

### Content
Edit the HTML content in `index.html` to update:
- Text content
- Images (replace files in `images/` folder)
- Links and navigation
- Button text and actions

### Styling
Modify `styles.css` to adjust:
- Typography
- Spacing
- Layout
- Animations

## Performance

- Optimized images from Figma
- Minimal JavaScript for smooth interactions
- CSS animations for better performance
- Responsive images with proper sizing

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Alt text for all images
- Keyboard navigation support
- High contrast color scheme
- Readable font sizes

## License

This project is open source and available under the MIT License.