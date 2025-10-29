# Consulting Website

A modern, one-page consulting website built with HTML and Tailwind CSS.

## Design System

### Colors
- **Primary**: `#2D3142` (Moonlit Grey) - Main background color
- **Accent**: `#7B2CBF` (Vivid Purple) - Highlights and CTAs
- **Gradients**: Purple → Blue transitions for visual interest

### Typography
- **Headers**: Poppins (400, 600, 700, 800)
- **Body Text**: DM Sans (400, 500, 700)
- **Numbers**: Monument Extended style (using Poppins Bold)

### Theme
- Dark, bold, high contrast design
- Glow effects on key elements
- Smooth transitions and hover states
- Purple/blue gradient accents

## Project Structure

```
/
├── index.html              # Main HTML file
├── package.json            # NPM configuration
├── README.md              # This file
└── src/
    ├── assets/
    │   ├── images/        # Image files
    │   └── fonts/         # Custom fonts (if needed)
    └── styles/
        └── custom.css     # Custom CSS with glow effects
```

## Tech Stack

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Google Fonts**: Poppins & DM Sans
- **Live Server**: Development server for hot-reload

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- NPM or Yarn

### Installation

1. Install dependencies:
```bash
npm install
```

### Development

Start the development server:
```bash
npm run dev
```

The site will be available at `http://localhost:3000`

The server will automatically reload when you make changes to the files.

## Sections

The website includes the following sections:

1. **Hero Section**: Bold headline with gradient text and CTAs
2. **Services Section**: Three service cards with numbered badges
3. **About Section**: Company info with stats and key benefits
4. **Contact Section**: Contact form for inquiries
5. **Footer**: Copyright and basic info

## Customization

### Colors
Colors are configured in the Tailwind config within `index.html`:
```javascript
colors: {
    'moonlit': '#2D3142',
    'vivid-purple': '#7B2CBF',
}
```

### Fonts
Fonts are loaded from Google Fonts. To change fonts, update the link in the `<head>` section.

### Content
Edit the HTML directly in `index.html` to update text, images, and structure.

### Glow Effects
Glow effects are defined in `src/styles/custom.css`:
- `.glow-text` - Text glow effect
- `.glow-button` - Button glow effect

## Features

- Fully responsive design
- Smooth scrolling navigation
- Hover effects and transitions
- Custom glow effects
- Gradient backgrounds
- Dark theme optimized
- No build process required
- Fast loading with CDN

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT

## Next Steps

Ready to add content and customize:
1. Replace placeholder text with your actual content
2. Add your logo and brand images
3. Update contact form to connect to your backend
4. Add more sections as needed
5. Deploy to your hosting provider
