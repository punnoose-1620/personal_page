# Personal Page Project

This is my personal website project that showcases my portfolio, skills, professional information, and medical history. The project is designed to be clean, modern, and easily maintainable.

## Live Website

Visit my personal website at: [https://punnoose-k-thomas.com/main.html](https://punnoose-k-thomas.com/main.html)

## Complete File Structure

```
personal_page/
├── 📄 HTML Files (Main Pages)
│   ├── main.html                    # Home page with personal introduction
│   ├── work_experience.html         # Professional work experience
│   ├── education.html               # Educational background
│   ├── projects.html                # Personal and academic projects
│   ├── certifications.html          # Professional certifications
│   ├── references.html              # Professional references
│   ├── medical-history.html         # Medical history and records
│   ├── 404.html                     # Custom 404 error page
│   └── helpful-artist-privacy-policy.html  # Privacy policy page
│
├── 🎨 Styling & Assets
│   ├── styles.css                   # Main CSS file for all pages
│   ├── logo_images/                 # Logo and icon assets
│   │   ├── punnoose_pic.ico         # Website favicon
│   │   ├── linkedin_logo.png        # LinkedIn icon
│   │   ├── github_logo.png          # GitHub icon
│   │   ├── phone_logo.jpg           # Phone icon
│   │   ├── office_mail_logo.png     # Office email icon
│   │   ├── gmail_logo.jpg           # Gmail icon
│   │   ├── profile_pic.png          # Profile picture
│   │   └── [other logo files]       # Various company and project logos
│   │
│   ├── bg_images/                   # Background images for projects
│   │   ├── profile_pic.jpg          # Header profile picture
│   │   ├── My_Life.webp             # Header background image
│   │   ├── [project backgrounds]    # Background images for each project
│   │   └── [institution images]     # University and company images
│   │
│   └── certification_images/        # Certification logos and images
│       ├── coursera.png             # Coursera certification
│       ├── nvidia.png               # NVIDIA certification
│       ├── bennett.png              # Bennett University
│       └── [other certifications]   # Various certification images
│
├── 📋 Configuration Files
│   ├── CNAME                        # Custom domain configuration
│   ├── LICENSE                      # MIT License
│   └── scopes.txt                   # API scope definitions (legacy)
│
└── 📚 Documentation
    └── README.md                    # This file - project documentation
```

## Page Descriptions & Connections

### Core Pages

1. **main.html** - Home Page
   - **Purpose**: Personal introduction and overview
   - **Content**: About me, contact information, downloadable resume
   - **Connections**: Links to all other pages via navigation
   - **Features**: Firebase analytics, interactive contact buttons

2. **work_experience.html** - Professional Experience
   - **Purpose**: Showcase work history and achievements
   - **Content**: Job positions, companies, projects, skills used
   - **Connections**: Referenced in main.html navigation
   - **Features**: Interactive cards with hover effects

3. **education.html** - Educational Background
   - **Purpose**: Display academic qualifications and achievements
   - **Content**: Degrees, institutions, projects, skills learned
   - **Connections**: Referenced in main.html navigation
   - **Features**: Expandable education cards

4. **projects.html** - Personal Projects
   - **Purpose**: Showcase technical projects and skills
   - **Content**: Project descriptions, technologies used, outcomes
   - **Connections**: Referenced in main.html navigation
   - **Features**: Project cards with background images

5. **certifications.html** - Professional Certifications
   - **Purpose**: Display professional qualifications and achievements
   - **Content**: Certification details, issuing organizations, dates
   - **Connections**: Referenced in main.html navigation
   - **Features**: Certification cards with logos

6. **references.html** - Professional References
   - **Purpose**: Provide professional references and testimonials
   - **Content**: Reference contact information and relationships
   - **Connections**: Referenced in main.html navigation
   - **Features**: Reference cards with contact details

7. **medical-history.html** - Medical Records
   - **Purpose**: Store and display medical history information
   - **Content**: Hospital visits, diagnoses, treatments, medications
   - **Connections**: Referenced in main.html navigation
   - **Features**: Medical cards, emergency contacts, Firebase analytics

### Supporting Files

8. **styles.css** - Main Stylesheet
   - **Purpose**: Centralized styling for all pages
   - **Content**: CSS rules for layout, colors, animations, responsiveness
   - **Connections**: Linked by all HTML files
   - **Features**: Responsive design, hover effects, consistent theming

9. **404.html** - Error Page
   - **Purpose**: Custom error page for broken links
   - **Content**: Error message and navigation back to main site
   - **Connections**: Automatically served for 404 errors

10. **CNAME** - Domain Configuration
    - **Purpose**: Configure custom domain for GitHub Pages
    - **Content**: Domain name: punnoose-k-thomas.com

## Asset Organization

### logo_images/
Contains all icons, logos, and small images used throughout the site:
- Contact icons (phone, email, LinkedIn, GitHub)
- Profile pictures
- Company and project logos
- Website favicon

### bg_images/
Contains background images for projects and institutions:
- Project background images (webp format for optimization)
- University and company images
- Profile pictures for headers

### certification_images/
Contains images related to professional certifications:
- Certification logos
- Institution logos
- Achievement badges

## Technical Features

### Analytics & Tracking
- **Firebase Analytics**: Integrated across all pages for visitor tracking
- **Event Tracking**: Clicks on contact links, downloads, page visits
- **IP Tracking**: Visitor location and device information

### Interactive Elements
- **Hover Effects**: Cards zoom and lift on hover
- **Clickable Elements**: Contact buttons, download links, navigation
- **Responsive Design**: Works on all device sizes
- **Smooth Transitions**: CSS animations for better UX

### Navigation System
- **Consistent Header**: Same header across all pages
- **Navigation Menu**: Links between all main pages
- **Footer Contact**: Consistent contact information
- **Breadcrumb Navigation**: Clear page hierarchy

## Deployment

This website is deployed using GitHub Pages and uses a custom domain from Namecheap. The deployment process is automated through GitHub Actions, which builds and deploys the site whenever changes are pushed to the main branch.

### Domain Configuration
- Primary domain: punnoose-k-thomas.com
- DNS management: Namecheap
- SSL certificate: Provided by GitHub Pages

### Deployment Workflow
1. Push changes to the main branch
2. GitHub Actions automatically builds the site
3. Changes are deployed to GitHub Pages
4. Site is accessible at https://punnoose-k-thomas.com/main.html

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Styling, animations, and responsive design
- **JavaScript**: Interactive elements and Firebase integration
- **Firebase**: Analytics and event tracking
- **Font Awesome**: Icons and visual elements
- **GitHub Pages**: Hosting and deployment

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/punnoose-1620/personal_page.git
cd personal_page
```

2. Open `main.html` in your web browser to view the website locally.

## Development

To make changes to the website:

1. Edit the HTML files to modify content
2. Update `styles.css` for styling changes
3. Modify JavaScript in HTML files for interactive features
4. Add new assets to the appropriate directories as needed

## Contributing

Feel free to submit issues and enhancement requests!

## License

MIT License