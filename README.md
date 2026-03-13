# CSC4035 Assignment 1: Responsive Portfolio Website

**Course:** CSC4035 Web Programming and Technologies  
**Student Name:** Joseph chipili 
**Student ID:** 2021396347
**Submission Date:** March 15, 2025  

## Design Theme

**Modern Professional Blue Theme**

My portfolio website features a clean, professional design with a blue color scheme that conveys trust, reliability, and expertise. The design follows modern web development trends with:
- Clean typography using system fonts for optimal performance
- Subtle shadows and hover effects for depth
- Rounded corners for approachability
- Generous white space for readability
- Consistent spacing throughout

## CSS Techniques Used

- ✅ **CSS Custom Properties** - Centralized color palette and spacing variables in `:root`
- ✅ **Flexbox** - Used in project cards, navigation, and footer layouts
- ✅ **CSS Grid** - Implemented in about section, projects grid, and contact section
- ✅ **Media Queries** - Three breakpoints (768px, 1024px, 1200px)
- ✅ **CSS Animations** - Fade-in animations on page load
- ✅ **CSS-only Hamburger Menu** - Pure CSS mobile navigation toggle
- ✅ **Print Stylesheet** - Optimized printing layout

## Bonus Features Implemented

1. **Dark/Light Mode Toggle (+3%)** - Automatic theme switching based on system preferences
2. **CSS Animations/Transitions (+3%)** - Smooth hover effects and entrance animations
3. **CSS-only Hamburger Menu (+2%)** - No JavaScript required for mobile navigation
4. **Print Stylesheet (+2%)** - Clean, printer-friendly version of the portfolio

**Total Bonus: +10%**

## Challenges & Solutions

### Challenge 1: CSS-only Hamburger Menu
**Solution:** I used the checkbox hack with the `:checked` pseudo-class to toggle the navigation menu. The label controls the checkbox visibility while providing visual hamburger icon that animates into an X when open.

### Challenge 2: Maintaining Consistent Spacing
**Solution:** I created CSS custom properties for spacing (`--spacing-xs` through `--spacing-xl`) to ensure consistent margins and padding throughout the site. This made responsive adjustments much easier.

### Challenge 3: Form Validation Styling
**Solution:** I used the `:valid` and `:invalid` pseudo-classes with the `:not(:placeholder-shown)` selector to show validation states only after user interaction, preventing empty fields from showing error states.

### Challenge 4: Responsive Images
**Solution:** I set explicit width and height attributes on images to prevent layout shift, combined with CSS `max-width: 100%` and `height: auto` for responsive scaling.

## Screenshots

The following screenshots demonstrate the responsive design at different breakpoints:

- **Mobile** (< 768px): `screenshots/mobile.png`
- **Tablet** (768px - 1024px): `screenshots/tablet.png`  
- **Desktop** (1024px+): `screenshots/desktop.png`

## Credits

### Images
- Profile image: [Placeholder.com](https://placeholder.com) - Generated placeholder
- Project images: [Placeholder.com](https://placeholder.com) - Generated placeholders

### Fonts
- System fonts stack: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif

### Icons & Resources
- No external icons used - pure CSS for all visual elements
- Color palette inspired by modern UI trends

## Testing

### Browser Testing
- ✅ Google Chrome (Latest)
- ✅ Mozilla Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Microsoft Edge (Latest)

### Responsive Testing
- ✅ Mobile (iPhone SE, 375px)
- ✅ Tablet (iPad, 768px)
- ✅ Desktop (1920x1080)
- ✅ Large Desktop (2560x1440)

### Accessibility Testing
- ✅ Semantic HTML structure
- ✅ Alt text on all images
- ✅ Proper heading hierarchy
- ✅ Color contrast (WCAG AA compliant)
- ✅ Keyboard navigation
- ✅ Focus indicators
- ✅ Skip link for screen readers

### Validation
- ✅ HTML5 validated with W3C Validator
- ✅ CSS3 validated with W3C Validator
- ✅ No JavaScript errors

## Academic Integrity Declaration

I hereby declare that:
- All code in this assignment is my own original work
- No CSS frameworks or libraries have been used
- Images are royalty-free placeholders or my own work
- Sources have been properly credited where applicable

**Signature:** Joseh chipili
**Date:** March 15, 2025











[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8NpkA7e4)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23071709&assignment_repo_type=AssignmentRepo)
# Assignment 1: Responsive Portfolio Website

**Course:** CSC4035 Web Programming and Technologies
**Weight:** 5% of final grade
**Due:** Week 6, Friday 11:59 PM

---

## Overview

Create a professional, responsive portfolio website showcasing your skills, projects, and contact information. This assignment assesses your HTML5 and CSS3 skills, including semantic markup, modern layout techniques (Flexbox/Grid), and responsive design principles.

**Important:** No CSS frameworks (Bootstrap, Tailwind, etc.) are allowed. All CSS must be hand-written.

---

## Requirements

### Functional Requirements

Your portfolio must include **4 or more sections**:

| Section | Required Content |
|---------|------------------|
| **Home/Hero** | Your name, tagline, and call-to-action button |
| **About** | Professional bio (150+ words), profile image, skills list |
| **Projects** | Minimum 3 project cards with title, description, image, and links |
| **Contact** | Contact form with validation attributes (name, email, message) |

### Technical Requirements

| Requirement | Description |
|-------------|-------------|
| **HTML5** | Valid semantic HTML (header, nav, main, section, article, footer) |
| **CSS3** | External stylesheet only (no inline styles) |
| **CSS Variables** | Use custom properties for colors and spacing |
| **Flexbox** | Use for at least one layout component |
| **CSS Grid** | Use for at least one layout component |
| **Responsive** | Mobile-first with minimum 3 breakpoints |
| **Accessibility** | Alt text, form labels, color contrast, heading hierarchy |

### Breakpoints Required

```css
/* Mobile-first base styles */

/* Tablet (768px and up) */
@media (min-width: 768px) { }

/* Desktop (1024px and up) */
@media (min-width: 1024px) { }

/* Large Desktop (1200px and up) - optional */
@media (min-width: 1200px) { }
```

---

## Project Structure

```
csc4035-assignment1-portfolio/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Main stylesheet
├── images/             # Your images (profile, projects, etc.)
├── screenshots/        # Screenshots at different breakpoints
│   ├── mobile.png
│   ├── tablet.png
│   └── desktop.png
└── README.md           # This file (update with your info)
```

---

## Getting Started

1. **Clone this repository** to your local machine
2. **Open `index.html`** in your code editor
3. **Complete the TODO comments** in each file
4. **Test responsiveness** using browser developer tools
5. **Take screenshots** at mobile, tablet, and desktop sizes
6. **Commit and push** your changes regularly

---

## Grading Rubric (100 points)

| Criterion | Points | Description |
|-----------|--------|-------------|
| **HTML Structure & Semantics** | 20 | Valid HTML5, semantic elements, proper document structure |
| **CSS Styling & Design** | 20 | Professional design, cohesive color scheme, typography |
| **Flexbox & Grid Usage** | 20 | Both techniques used appropriately and effectively |
| **Responsive Design** | 20 | Mobile-first, 3+ breakpoints, no horizontal scrolling |
| **Content & Completeness** | 10 | All sections complete with quality content |
| **Code Quality** | 10 | Clean, organized, well-commented code |

### Automated Tests (40% of grade)

The following are checked automatically on each push:
- HTML validation (no errors)
- Required HTML elements present
- CSS file linked correctly
- Required sections exist
- Responsive meta tag present

---

## Submission Checklist

Before submitting, verify:

- [ ] All 4 sections are complete (Home, About, Projects, Contact)
- [ ] HTML validates with no errors
- [ ] CSS uses custom properties (variables)
- [ ] Flexbox is used for at least one component
- [ ] CSS Grid is used for at least one component
- [ ] Site is responsive at all breakpoints
- [ ] All images have alt text
- [ ] Form inputs have labels
- [ ] Screenshots added to `/screenshots` folder
- [ ] README updated with your information

---

## Your Information

**Name:** [Your Name]
**Student ID:** [Your Student ID]
**Design Theme:** [Describe your portfolio theme/style]

### CSS Techniques Used
- [ ] CSS Custom Properties
- [ ] Flexbox
- [ ] CSS Grid
- [ ] Media Queries
- [ ] Other: _______________

### Challenges & Solutions
[Describe any challenges you faced and how you solved them]

### Credits
[List any images, fonts, or resources used with attribution]

---

## Academic Integrity

- All code must be your own work
- No CSS frameworks or libraries allowed
- Images must be royalty-free or your own (credit sources)
- Plagiarism detection tools will be used

**Violations result in zero marks and academic misconduct reporting.**

---

## Extension Opportunities (Bonus: up to +10%)

- Dark/light mode toggle with CSS (+3%)
- CSS animations/transitions (+3%)
- CSS-only hamburger menu (+2%)
- Print stylesheet (+2%)
