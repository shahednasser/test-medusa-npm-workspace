# Medusa Monorepo

A monorepo powered by Turborepo containing a Medusa backend and Next.js storefront.

## What's inside?

This monorepo includes the following apps:

- `backend`: A Medusa v2 backend application
- `storefront`: A Next.js storefront application

## Getting Started

### Installation

Install dependencies from the root:

```bash
npm install
```

### Development

Run all apps in development mode:

```bash
npm run dev
```

This will start:
- Backend on http://localhost:9000
- Storefront on http://localhost:8000

### Build

Build all apps:

```bash
npm run build
```

### Running Individual Apps

You can run specific apps using Turbo's filtering:

```bash
# Run backend only
npm run dev -- --filter=backend

# Run storefront only
npm run dev -- --filter=storefront
```

## Useful Commands

- `npm run dev` - Start all apps in development mode
- `npm run build` - Build all apps
- `npm run start` - Start all apps in production mode
- `npm run lint` - Lint all apps
- `npm run test` - Run tests across all apps
- `npm run clean` - Clean build artifacts and node_modules

## Turborepo

This monorepo uses [Turborepo](https://turbo.build/repo) for:

- Fast, incremental builds
- Remote caching
- Parallel execution
- Task pipelines

Learn more about Turborepo at [turbo.build](https://turbo.build/repo).
