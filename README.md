# MU Beauty Salon & Spa — Official Website

Live: https://mubeauty.com (your Route 53 domain)
Hosted on: **AWS S3 + Route 53 + CloudFront** — Created & deployed by me

### Overview
Modern luxury salon website for AD Plazza, Old Ashongman, Shop 5. Built for real clients to walk-in or book online.

**Tagline:** Beauty. Confidence. Elegance.

### Services
- Men's & Women's Haircut
- Braiding & Hairstyling
- Pedicure & Manicure
- Makeup & Nail Extension
- Wig Making & Installation
- Spa & Body Treatments

### Features
- Responsive dark/gold luxury theme
- Book Now CTA -> Appointment form
- Get In Touch: +233504077879 | Hours: Tue-Sat 9AM-7PM, Sun 1PM-7PM
- Find Us: Google Maps embed + AD Plazza landmark
- SEO optimized, fast loading via CloudFront CDN

### AWS Architecture
**S3 (Static Website Hosting) -> CloudFront (CDN/HTTPS) -> Route 53 (Custom Domain) -> ACM Certificate**

- Bucket: `mu-beauty-salon-website`
- Public access via CloudFront OAC, S3 Block Public Access ON
- Route 53 A record -> CloudFront distribution
- Cost: < $1/month

### Tech Stack
HTML5, CSS3, JavaScript, AWS S3, Route 53, CloudFront

Built: Oct 2026 by Simon Kofi Duku
