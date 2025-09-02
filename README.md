# Niyantri Dog Care - Project Overview

This is a static multi-page website for a dog grooming business named "Niyantri Dog Care" located in Hyderabad, India. It uses Tailwind CSS for styling, a subtle page load fade-in, and scroll fade-ins for sections. The site includes a shopping cart with a mock PayPal checkout flow.

Pages included:
- index.html (Home)
- menu.html (Service items available for grooming)
- cart.html (Cart and checkout prompt)
- about.html (About the company)
- contact.html (Contact information and form)

Key features:
- Consistent header and footer across all pages
- Mobile responsive navigation with a hamburger menu
- Tailwind CSS-based styling
- Placeholder images using the required syntax: src="https://images.unsplash.com/photo-1635405050330-b0824eb1bf26?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3ODkyNDZ8MHwxfHNlYXJjaHwxfHxkZXNjcmlwdGlvbnxlbnwwfDB8fHwxNzU2NzE0MzIxfDA&ixlib=rb-4.1.0&q=80&w=1080"
- Cart state stored in localStorage as an array of objects: { id, name, price, quantity }
- PayPal-like mock checkout process with a simulated API call
- Basic image carousel using Swiper.js on the home page
- Inline SVG icons throughout (no external image assets required)

Notes:
- The current year is automatically set to 2025 for the footer copyright as requested.
- All interactive elements use Tailwind CSS classes for transitions and hover effects.
- The address placeholder on the contact page uses Hyderabad, India as required.

How to run:
- Simply open the HTML files in a modern browser. No server is required since this is client-side only.

If you’d like any content adjusted (tone, colors, or additional services), I can update the files quickly.
