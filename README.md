# ActionTech AI Creative Program

Marketing website for ActionTech's AI Creative Coding education program for kids (K-12).

## Overview

This is the official website for ActionTech AI Education, featuring:

- **Course Introduction**: AI-powered creative coding curriculum
- **Free Trial Class**: Registration and scheduling
- **Summer Program**: Intensive summer coding camps
- **Pricing & Enrollment**: Course packages and signup

## Tech Stack

- Pure HTML/CSS (no build process required)
- Responsive design for mobile and desktop
- MJPEG video support

## Structure

```
ActionTech-Website/
├── index.html      # Main website page
├── CNAME           # Custom domain configuration
├── images/         # Course images and graphics
│   ├── course/     # Course feature images
│   ├── icons/      # UI icons
│   └── photos/     # Student photos
└── videos/         # Demo videos and tutorials
```

## Deployment

The website is deployed via GitHub Pages.

### Custom Domain

- Domain configured in `CNAME` file
- DNS records point to GitHub Pages

### Local Development

Simply open `index.html` in a browser - no build process needed.

```bash
# macOS
open index.html

# Or use any local server
python3 -m http.server 8080
```

## Content Updates

To update website content:

1. Edit `index.html` directly
2. Add/replace images in `images/` folder
3. Commit and push to `main` branch
4. Changes deploy automatically via GitHub Pages

## License

Copyright (c) 2024-2026 ActionTech AI Education. All rights reserved.
