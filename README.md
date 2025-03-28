# AI Content Agent

This is an AI-powered content analysis platform that helps content creators get insights from their YouTube videos. The platform uses advanced AI to analyze video content, generate transcriptions, create thumbnails, and provide content recommendations.

Repository: [https://github.com/sonnysangha/5-day-challenge-ai-agent-saas-challenge-nextjs-15-schematic-clerk.git](https://github.com/sonnysangha/5-day-challenge-ai-agent-saas-challenge-nextjs-15-schematic-clerk.git)

## Features

- 📊**AI Video Analysis** - Deep insights into your video content with advanced AI analysis
- 📝**Smart Transcription** - Accurate transcriptions of your videos for subtitles or repurposing content
- 🎨**Thumbnail Generation** - AI-generated eye-catching thumbnails to boost click-through rates
- 🔍**Title Generation** - SEO-optimized title suggestions that resonate with your audience
- 🎬**Shot Script** - Detailed instructions to recreate viral videos with shooting techniques and editing tips
- 🤖**AI Agent Conversations** - Engage in discussions about content strategy with your AI agent companion

## Tech Stack

- **Frontend**: Next.js 15, React 19, TailwindCSS
- **AI Integration**: AI SDK, Anthropic, OpenAI
- **Authentication**: Clerk
- **Database**: Convex
- **Styling**: Tailwind CSS, Radix UI components
- **YouTube Integration**: youtubei.js for video data extraction

## Project Structure

- `/app` - Next.js app directory with pages and layouts
- `/components` - Reusable UI components
- `/convex` - Database models and schema
- `/actions` - Server actions for form handling and business logic
- `/lib` - Utility functions and helper methods
- `/features` - Feature flag configurations
- `/public` - Static assets

## Data Model

The application stores:

- YouTube video IDs linked to users
- Video transcripts with timestamps
- Generated images/thumbnails
- Custom generated titles

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Environment Setup

The project requires several environment variables to be set up. Check `.env.example` for required configurations.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
