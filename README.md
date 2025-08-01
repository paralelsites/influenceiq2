# InfluenceIQ - AI-Powered Influence Marketing Platform

A professional influence marketing services website featuring:
- Modern dark theme with purple accents
- AI algorithm positioning for competitive advantage
- Direct email contact approach (no free consultations)
- Comprehensive service packages and case studies
- Mobile-responsive design with smooth animations

## 🚀 Deployment Options

### GitHub Pages (Recommended - Free)

1. **Build the static version:**
   ```bash
   node build-static.js
   ```

2. **Deploy to GitHub Pages:**
   - Copy all files from `dist/` folder to your GitHub Pages repository
   - Files will be available at: `https://yourusername.github.io/your-repo-name`

### Replit Deployment

For the full-stack version with backend analytics:
- Use the "Deploy" button in Replit
- The app will be available at your Replit deployment URL

## 📁 Project Structure

```
├── client/
│   ├── src/
│   │   ├── components/sections/    # Website sections
│   │   ├── pages/                  # Page components
│   │   ├── App.tsx               # Full-stack app
│   │   └── App-static.tsx        # Static version
│   ├── index.html                # Full-stack entry
│   └── index-static.html         # Static entry
├── server/                       # Backend API
├── dist/                        # Built static files
├── build-static.js             # Static build script
└── vite.config.static.ts       # Static build config
```

## 🎨 Features

- **AI Algorithm Positioning:** Comprehensive explanation of proprietary matching technology
- **Professional Design:** Dark theme with consistent purple accent colors
- **Email Contact Integration:** All CTAs link to structured email templates
- **Case Studies:** Real-world success stories with metrics
- **Service Packages:** Three-tier pricing structure
- **Mobile Responsive:** Optimized for all device sizes
- **Smooth Animations:** Framer Motion powered interactions

## 📧 Email Integration

All contact points use `mailto:hello@influenceiq.com` with structured subjects:
- General inquiries
- Package-specific requests  
- Demo requests
- Support requests

## 🛠 Development

**Start development server:**
```bash
npm run dev
```

**Build static version:**
```bash
node build-static.js
```

**Preview static build:**
```bash
npm run preview:static
```

## 📱 Contact

- Email: hello@influenceiq.com
- Phone: +1 (555) 123-4567

---

Ready for immediate deployment to GitHub Pages or any static hosting platform!
