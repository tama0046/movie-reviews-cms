# Movie Reviews - Headless CMS Backend

> Strapi headless CMS backend for our Interactive Media Design movie review website project.

## Project Information

**Assignment:** Headless CMS Review Site  
**Course:** Interactive Media Design - Algonquin College  
**Due Date:** December 11, 2025  

### Review Site Details
- **Type of Review Site:** Movie Reviews
- **Headless CMS Choice:** Strapi
- **Frontend Tool:** Vue 3 with Vite
- **CSS Framework:** Bootstrap 5

## Team Members

Role            Name              Student Number    GitHub
Team Leader     Manoj Tamang      tama0046          @tama0046
Member 2        Saskar baniya     bani0029          @bani0029
Member 3        Roland            park0625          @park0625

## Technologies Used

- **CMS:** Strapi v4
- **Runtime:** Node.js
- **API:** REST API
- **Database:** SQLite (Development) / PostgreSQL (Production)

## Content Structure

### Movie Review Content Type
- Title (Text)
- Poster Image (Media)
- Review (Rich Text)
- Rating (Number: 1-5)
- Release Year (Number)

**Total Reviews:** 10+ movie reviews

## Setup Instructions
```bash
# Clone the repository
git clone https://github.com/tama0046/movie-reviews-cms.git

# Navigate to project directory
cd REPO-NAME

# Install dependencies
npm install

# Start development server
npm run develop
```

## API Endpoints
```
GET  /api/movie-reviews          - Get all movie reviews
GET  /api/movie-reviews/:id      - Get single movie review
GET  /api/movie-reviews?populate=* - Get reviews with images
```

## Deployment

- **Production API:** [URL to be added after deployment]

---

**Companion Repository:** https://github.com/tama0046/movie-reviews-frontend.git