# Maharashtra Mandal Krakow - Website Specification

## Project Overview
- **Project Name**: Maharashtra Mandal Krakow Website
- **Type**: Static website with blog/events system
- **Core Functionality**: Cultural group website showcasing Marathi culture, events, and community activities in Krakow, Poland
- **Target Users**: Marathi diaspora, Indian community members, cultural enthusiasts in Krakow

## UI/UX Specification

### Layout Structure
- **Header**: Fixed navigation with logo, menu links
- **Hero**: Full-width hero section with background image and tagline
- **Sections**: Home, About, Events, Gallery, Contact
- **Footer**: Social links, copyright, quick links

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

### Visual Design

#### Color Palette
- **Primary**: #FF6B35 (Saffron/Orange - represents Maharashtra)
- **Secondary**: #1A1A2E (Deep Navy - elegant dark)
- **Accent**: #FFD700 (Gold - prosperity/celebration)
- **Background**: #0F0F1A (Dark background)
- **Surface**: #1E1E32 (Card backgrounds)
- **Text Primary**: #FFFFFF
- **Text Secondary**: #B0B0C0

#### Typography
- **Headings**: 'Playfair Display', serif (elegant, cultural feel)
- **Body**: 'Poppins', sans-serif (modern, readable)
- **Marathi Text**: 'Tiro Marathi', serif

#### Spacing System
- Section padding: 80px vertical, 5% horizontal
- Card padding: 24px
- Component gaps: 16px / 24px / 32px

#### Visual Effects
- Subtle gradient overlays on hero
- Card hover animations (transform, shadow)
- Smooth scroll behavior
- Fade-in animations on scroll
- Glassmorphism effects on cards

### Components

#### Navigation
- Logo on left
- Menu items: Home, About, Events, Gallery, Contact
- Mobile: hamburger menu
- Active state: underline with accent color

#### Hero Section
- Full viewport height
- Background image with dark overlay
- Main title with animation
- Tagline
- CTA buttons

#### About Section
- Mission statement
- Key highlights/cards
- Statistics or achievements

#### Events Section
- Upcoming events calendar (timeline view)
- Event cards with date, title, description
- Filter by event type
- "View All Events" link to blog

#### Gallery Section
- Photo grid with lightbox
- Video embeds (YouTube, Facebook, Instagram)
- Tab navigation for Photos/Videos

#### Blog/Events Section
- Markdown-based event posts
- Post list with thumbnails
- Single post view with full content
- Support for images, videos in posts

#### Contact Section
- Contact form
- Location details
- Social media links

#### Footer
- Logo and description
- Quick links
- Social media icons
- Copyright

## Functionality Specification

### Core Features
1. **Responsive Navigation**: Smooth mobile menu
2. **Event Calendar**: Visual timeline of upcoming events
3. **Blog System**: Markdown-based posts in /events folder
4. **Gallery**: Photo grid with lightbox, video embeds
5. **Contact Form**: Functional form (Netlify Forms ready)
6. **Social Integration**: Links to Facebook, Instagram, YouTube

### User Interactions
- Smooth scroll to sections
- Hover effects on cards/buttons
- Lightbox for gallery images
- Video embedding from YouTube/Facebook/Instagram
- Form validation

### Data Handling
- Events stored as markdown files in /events/
- Images in /images/
- Gallery images in /gallery/

### Edge Cases
- No events: Show "Coming Soon" message
- Missing images: Fallback placeholder
- Mobile navigation: Proper touch handling

## Technical Stack
- Static HTML/CSS/JS
- No build step required (Netlify auto-deploys)
- Markdown for event posts (parsed at build time via Netlify CMS or manual)
- Netlify Forms for contact form

## Acceptance Criteria
1. Website loads without errors
2. All sections are visible and properly styled
3. Navigation works on all devices
4. Events section shows upcoming events
5. Gallery displays photos and video embeds
6. Contact form is functional (Netlify Forms)
7. Mobile responsive
8. Fast loading (optimized images)
9. SEO friendly (meta tags)
10. Git-ready for Netlify deployment
