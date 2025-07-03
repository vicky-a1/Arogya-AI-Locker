# Arogya AI Health Twin

A comprehensive health management application that creates a digital twin of your health profile, manages your health records, and provides personalized health insights.

## Features

- Digital Health Twin
- Health ID Creation
- Health Locker for storing medical records
- Family Health Manager
- Health Analytics
- Wearable Health Data Integration
- Doctor Dashboard
- Patient Dashboard
- Notification Center
- Multi-language Support

## Tech Stack

- React
- TypeScript
- Vite
- Tailwind CSS
- Shadcn UI Components
- React Router
- React Query
- React Hook Form
- Zod (for validation)

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd arogya-ai-health-twin

# Install dependencies
npm install

# Start the development server
npm run dev
```

The application will be available at http://localhost:5173 (or another port if 5173 is in use).

### Building for Production

```bash
npm run build
```

This will create a `dist` directory with the built application.

## Deployment

This application is configured for deployment on:

- Vercel
- Render
- Netlify

See the [Deployment Guide](./DEPLOYMENT.md) for detailed instructions.

## Environment Variables

Copy the `.env.example` file to `.env` and update the values as needed.

```bash
cp .env.example .env
```

## License

MIT
