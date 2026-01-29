# 🎵 Music School Website

A modern, interactive music school website built with Next.js 16, React 19, TypeScript, and Tailwind CSS. Features beautiful UI components from Aceternity UI with smooth animations powered by Framer Motion.

## ✨ Features

- **Hero Section** with animated spotlight effect
- **Featured Courses** showcase with interactive hover cards
- **Infinite Testimonials** carousel with moving cards
- **Instructor Profiles** with animated tooltips and wavy background
- **Responsive Design** optimized for all devices
- **Dark Mode** support
- **Modern UI Components** with smooth animations
- **Grid & Dot Backgrounds** for visual appeal

## 🚀 Tech Stack

- **Framework:** Next.js 16.1.6 (App Router)
- **React:** 19.2.3
- **TypeScript:** 5.x
- **Styling:** Tailwind CSS 4.x
- **Animations:** Framer Motion 12.29.2
- **UI Components:** Custom components inspired by Aceternity UI
- **Utilities:**
  - `clsx` & `tailwind-merge` for className management
  - `simplex-noise` for wavy background effects
  - `mini-svg-data-uri` for SVG patterns

## 📦 Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd musicnextjs
```

2. Install dependencies:

```bash
npm install
```

3. Run the development server:

```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

## 📁 Project Structure

```
musicnextjs/
├── src/
│   ├── app/
│   │   ├── globals.css       # Global styles
│   │   ├── layout.tsx        # Root layout
│   │   └── page.tsx          # Home page
│   ├── components/
│   │   ├── ui/               # Reusable UI components
│   │   │   ├── animated-tooltip.tsx
│   │   │   ├── infinite-moving-cards.tsx
│   │   │   ├── moving-border.tsx
│   │   │   ├── navbar-menu.tsx
│   │   │   ├── Spotlight.tsx
│   │   │   └── wavy-background.tsx
│   │   ├── FeaturedCourses.tsx
│   │   ├── HeroSection.tsx
│   │   ├── Instructors.tsx
│   │   ├── Navbar.tsx
│   │   └── TestimonialCards.tsx
│   ├── data/
│   │   └── music_courses.json
│   └── utils/
│       └── cn.ts             # Utility functions
├── public/                   # Static assets
├── tailwind.config.ts        # Tailwind configuration
├── next.config.ts            # Next.js configuration
└── tsconfig.json            # TypeScript configuration
```

## 🎨 Key Components

### HeroSection

Landing section with spotlight animation and call-to-action

### FeaturedCourses

Displays featured music courses with hover effects

### TestimonialCards

Infinite scrolling testimonial cards from students

### Instructors

Meet the team section with animated instructor profiles

### UI Components

- **Spotlight**: Animated spotlight effect
- **WavyBackground**: Dynamic wavy background animation
- **InfiniteMovingCards**: Auto-scrolling card carousel
- **AnimatedTooltip**: Hover tooltips with smooth animations
- **MovingBorder**: Animated border button component

## 🎯 Custom Tailwind Configuration

The project includes custom Tailwind plugins for:

- Grid backgrounds (`bg-grid-*`)
- Dot patterns (`bg-dot-*`)
- CSS color variables
- Custom animations (spotlight, scroll)

## 🌐 Deployment

### Deploy on Vercel

The easiest way to deploy:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

1. Push your code to GitHub
2. Import your repository to Vercel
3. Vercel will automatically detect Next.js and configure the build
4. Your site will be live!

### Other Platforms

This Next.js app can be deployed to any platform that supports Node.js:

- Netlify
- AWS Amplify
- Digital Ocean
- Railway

## 📝 Configuration

### Environment Variables

Create a `.env.local` file for environment-specific variables (if needed).

### Tailwind CSS

Customize colors, fonts, and animations in `tailwind.config.ts`.

### Course Data

Edit course information in `src/data/music_courses.json`.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- UI components inspired by [Aceternity UI](https://ui.aceternity.com)
- Built with [Next.js](https://nextjs.org)
- Styled with [Tailwind CSS](https://tailwindcss.com)
- Animations by [Framer Motion](https://www.framer.com/motion)

---

Built with ❤️ for music education
