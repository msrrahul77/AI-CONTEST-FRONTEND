🚀 ReceiptIQ — AI-Powered Finance Management App

ReceiptIQ is a modern personal finance web application that helps users track expenses, manage budgets, and improve financial habits using AI-powered tools and smart automation.

✨ Main Features
📷 Scan receipts using AI-powered OCR
🤖 Chat with an AI financial assistant powered by Gemini
🎯 Set savings goals and get personalized financial tips
📊 View spending insights with interactive charts
📄 Export financial reports as PDFs with AI-generated summaries
🌗 Dark and light mode support
📱 Progressive Web App (PWA) with offline support
🔐 Secure authentication and protected routes
🎨 Explore smart budget templates
🗺️ Interactive onboarding for new users
🛡️ Role-based admin dashboard
📧 Newsletter subscription system
❓ FAQ, contact, and privacy pages
🌟 Unique Highlights
🤖 Smart AI Assistant

An AI-powered assistant that analyzes spending habits, detects unusual expenses, and provides personalized financial suggestions.

🎯 AI Goal Coaching

Users can create financial goals and receive customized guidance based on their real spending behavior.

📄 AI PDF Reports

Generate professional financial reports with AI-written monthly summaries.

⚡ High Performance

Built with Next.js 16, Turbopack, and PWA support for fast performance and offline functionality.
ReceiptIQ-frontend/
├── public/                     # Static assets & PWA manifest
│   └── screenshot.png
│
├── src/
│   ├── app/                    # Next.js App Router
│   │   ├── about/              # About us & mission page
│   │   ├── contact/            # Contact page with RHF + Zod
│   │   ├── dashboard/          # Protected dashboard area
│   │   │   ├── admin/          # Admin-only panel
│   │   │   ├── goals/          # Goal tracking & coaching
│   │   │   ├── profile/        # User profile management
│   │   │   ├── receipts/       # Receipt upload & history
│   │   │   ├── layout.tsx      # Dashboard shell layout
│   │   │   └── page.tsx        # Main dashboard page
│   │   ├── explore/            # Budget template explorer
│   │   ├── privacy-policy/     # Legal / privacy page
│   │   ├── globals.css         # Global styles & CSS variables
│   │   ├── layout.tsx          # Root layout with providers
│   │   ├── not-found.tsx       # Custom 404 page
│   │   ├── page.tsx            # Landing page (Hero + sections)
│   │   └── providers.tsx       # App-wide React providers
│   │
│   ├── components/
│   │   ├── features/           # Landing page section components
│   │   │   ├── AgenticChat.tsx
│   │   │   ├── CTABanner.tsx
│   │   │   ├── FAQ.tsx
│   │   │   ├── FinancialOnboardingModal.tsx
│   │   │   ├── GameChangingFeatures.tsx
│   │   │   ├── GoalCoach.tsx
│   │   │   ├── HowItWorks.tsx
│   │   │   ├── ImpactMetrics.tsx
│   │   │   ├── Newsletter.tsx
│   │   │   ├── PlatformCapabilities.tsx
│   │   │   ├── SmartFeatures.tsx
│   │   │   └── Testimonials.tsx
│   │   ├── providers/          # Context providers (Lenis, Theme, Query)
│   │   ├── shared/             # Navbar, Footer, shared UI
│   │   └── ui/                 # shadcn/ui base components
│   │
│   ├── data/                   # Static data & mock content
│   ├── hooks/                  # Custom React hooks
│   │   ├── useChat.ts          # AI chat state management
│   │   ├── useDebounce.ts      # Input debouncing
│   │   ├── useGoals.ts         # Goals CRUD
│   │   ├── useReceipts.ts      # Receipts data fetching
│   │   └── useSettings.ts      # User settings
│   └── lib/
│       ├── auth-client.ts      # better-auth browser client
│       └── utils.ts            # cn() + utility helpers
│
├── .env.local                  # Local environment variables
├── next.config.ts              # Next.js + PWA + API rewrite config
├── tailwind.config.ts          # Tailwind CSS v4 config
├── tsconfig.json               # TypeScript config
└── package.json

🎨 Premium User Experience

Smooth animations and responsive design using GSAP, Framer Motion, and Lenis.

🛠️ Tech Stack
Category	Technology
Frontend	Next.js 16, TypeScript
Styling	Tailwind CSS v4, shadcn/ui
State Management	Zustand, TanStack Query
Authentication	better-auth
Forms & Validation	React Hook Form, Zod
Charts	Recharts
AI	Google Gemini API
Animation	GSAP, Framer Motion, Lenis
PWA	next-pwa
Deployment	Vercel & Render
💼 Recruiter-Friendly Summary

Built ReceiptIQ, an AI-powered personal finance platform that allows users to scan receipts, track expenses, manage savings goals, and receive AI-driven financial insights. Developed using Next.js 16, TypeScript, Tailwind CSS, Zustand, TanStack Query, and Google Gemini API with a strong focus on performance, scalability, and user experience.
