# company-x-management-system

# Company X Management System

A modern web-based management system built to streamline and centralize company operations through a structured and responsive interface.

## Tech Stack

* **Next.js** — React framework for building the web application
* **TypeScript** — Type-safe JavaScript development
* **SCSS** — Modular and maintainable styling

## Features

* Company management dashboard
* Responsive user interface
* Structured management modules
* Reusable UI components
* Type-safe application development
* SCSS-based styling and customization

## Project Structure

```text
company-x-management-system/
│
├── frontend/                 # Next.js application
│   ├── public/
│   ├── src/
│   │   ├── app/
│   │   │   ├── login/
│   │   │   ├── dashboard/
│   │   │   ├── employees/
│   │   │   └── layout.tsx
│   │   │
│   │   ├── components/
│   │   │   ├── ui/
│   │   │   └── layout/
│   │   │
│   │   ├── services/        # API calls
│   │   ├── hooks/
│   │   ├── types/
│   │   ├── utils/
│   │   └── styles/
│   │
│   ├── .env.local
│   ├── package.json
│   └── tsconfig.json
│
├── backend/                  # Backend API
│   ├── src/
│   │   ├── controllers/
│   │   ├── services/
│   │   ├── routes/
│   │   ├── models/
│   │   ├── middleware/
│   │   ├── config/
│   │   └── utils/
│   │
│   ├── .env
│   └── package.json
│
├── .gitignore
└── README.md
```

> The structure may change as the project grows.

## Requirements

Make sure you have the following installed:

* Node.js 18.18 or later
* npm, yarn, pnpm, or bun

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Navigate to the project directory:

```bash
cd company-x-management-system
```

Install dependencies:

```bash
npm install
```

## Environment Variables

Create a `.env.local` file in the project root:

```env
NEXT_PUBLIC_API_URL=your_api_url
```

Add other environment variables as required by the project.

> Do not commit `.env.local` or other files containing sensitive credentials.

## Development

Start the development server:

```bash
npm run dev
```

The application will be available at:

```text
http://localhost:3000
```

## Production Build

Create a production build:

```bash
npm run build
```

Start the production server:

```bash
npm run start
```

## Code Quality

Before committing changes, make sure the project builds successfully:

```bash
npm run build
```

Follow the project's existing TypeScript, React, and SCSS conventions when adding new features.

## Styling

The project uses **SCSS** for styling.

Recommended organization:

```text
src/
├── styles/
│   ├── variables.scss
│   ├── mixins.scss
│   ├── globals.scss
│   └── ...
└── components/
    └── ComponentName/
        ├── ComponentName.tsx
        └── ComponentName.scss
```

Keep component-specific styles close to their respective components and place shared variables, mixins, and global styles in the shared styles directory.

## Development Guidelines

* Use **TypeScript** for all application code.
* Prefer reusable React components.
* Keep components focused on a single responsibility.
* Avoid unnecessary duplication.
* Use meaningful and consistent naming conventions.
* Keep API-related logic separate from UI components.
* Use SCSS for component and application styling.
* Ensure layouts are responsive across desktop and mobile devices.
* Do not commit environment variables, credentials, or other sensitive information.

## Git Workflow

Create a feature branch before working on a new feature:

```bash
git checkout -b feature/feature-name
```

For bug fixes:

```bash
git checkout -b fix/bug-name
```

Commit changes using clear messages:

```bash
git add .
git commit -m "feat: add employee management"
```

Push the branch:

```bash
git push origin feature/feature-name
```

## Available Scripts

| Command         | Description                       |
| --------------- | --------------------------------- |
| `npm run dev`   | Starts the development server     |
| `npm run build` | Creates a production build        |
| `npm run start` | Starts the production server      |
| `npm run lint`  | Runs the project's linting checks |

## License

This project is proprietary software developed for **Company X**.

Unauthorized copying, distribution, or modification of this project is prohibited.
