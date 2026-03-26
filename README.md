# first-repository

A starter repository containing an Angular application scaffolded with the Angular CLI.

## Repository Structure

```
first-repository/
└── angular-starter/   # Angular 21 application
```

## Angular Starter

The `angular-starter` project is a minimal Angular 21 application built with:

- **[Angular 21](https://angular.dev/)** – component-based frontend framework
- **[TypeScript 5.9](https://www.typescriptlang.org/)** – typed JavaScript
- **[RxJS 7](https://rxjs.dev/)** – reactive programming utilities
- **[Vitest](https://vitest.dev/)** – fast unit test runner
- **[Prettier](https://prettier.io/)** – code formatter

## Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- [npm](https://www.npmjs.com/) 11+

## Getting Started

```bash
# Navigate to the Angular project
cd angular-starter

# Install dependencies
npm install

# Start the development server
npm start
```

Open your browser at **http://localhost:4200/**. The app reloads automatically on file changes.

## Available Scripts

| Command | Description |
|---|---|
| `npm start` | Start the development server |
| `npm run build` | Build the app for production (output: `dist/`) |
| `npm run watch` | Build in watch mode for development |
| `npm test` | Run unit tests with Vitest |

## Building for Production

```bash
cd angular-starter
npm run build
```

Build artifacts are placed in the `dist/` directory and are optimized for performance.

## Running Tests

```bash
cd angular-starter
npm test
```

Unit tests are executed using [Vitest](https://vitest.dev/).

## Code Scaffolding

Use the Angular CLI to generate new components, directives, pipes, and more:

```bash
# Generate a new component
npx ng generate component component-name

# See all available schematics
npx ng generate --help
```

## Additional Resources

- [Angular Documentation](https://angular.dev/)
- [Angular CLI Reference](https://angular.dev/tools/cli)
- [Vitest Documentation](https://vitest.dev/)

