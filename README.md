# Storybook Demo

A React application demonstrating Storybook integration for component development and documentation. This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) and configured with [Storybook](https://storybook.js.org/) for isolated component development.

## Overview

This demo project showcases how to integrate Storybook into a React application. Storybook is an open-source tool for developing UI components in isolation, making it easier to build, test, and document components independently from your application.

## Features

- React 16.6+ application
- Storybook 4.0+ for component development
- Storybook Addons (Actions, Links)
- Storybook Deployer for GitHub Pages deployment
- Example component stories

## Prerequisites

- Node.js (v10 or higher recommended)
- npm or yarn package manager

## Installation

```bash
# Install dependencies
npm install
# or
yarn install
```

## Available Scripts

### React App Scripts

#### `npm start` or `yarn start`

Runs the React app in development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits. You will also see any lint errors in the console.

#### `npm test` or `yarn test`

Launches the test runner in interactive watch mode.
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build` or `yarn build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.

### Storybook Scripts

#### `npm run storybook` or `yarn storybook`

Starts Storybook in development mode on port 9009.
Open [http://localhost:9009](http://localhost:9009) to view your component stories.

This allows you to develop and test components in isolation without running the full application.

#### `npm run build-storybook` or `yarn build-storybook`

Builds a static version of Storybook to the `storybook-static` folder.
This can be deployed to any static hosting service.

#### `npm run deploy-storybook` or `yarn deploy-storybook`

Deploys the Storybook to GitHub Pages.
Requires proper Git repository configuration and GitHub Pages setup.

## Project Structure

```
storybook-demo/
├── .storybook/          # Storybook configuration
│   ├── addons.js        # Storybook addons registration
│   └── config.js        # Storybook main configuration
├── public/              # Public assets
├── src/
│   ├── stories/         # Component stories
│   │   └── index.js     # Example stories (Welcome, Button, etc.)
│   ├── App.js           # Main React component
│   ├── App.css          # App styles
│   ├── index.js         # Application entry point
│   └── ...
├── package.json         # Project dependencies and scripts
└── README.md           # This file
```

## What's in the Demo

The project includes several example stories to demonstrate Storybook capabilities:

- **Welcome Story**: Introduction to Storybook with navigation
- **Button Stories**: Interactive button components with different variations
- **GitHub Pages Story**: Simple example for deployment testing

## Technologies Used

- **React** (16.6.3): JavaScript library for building user interfaces
- **Create React App** (2.1.1): Build tooling and configuration
- **Storybook** (4.0.11): UI component development environment
- **Storybook Addons**:
  - Actions: View event handler interactions
  - Links: Navigate between stories
- **Storybook Deployer**: Deploy Storybook to GitHub Pages

## Development Workflow

1. **Develop Components**: Create React components in the `src` directory
2. **Write Stories**: Add stories for your components in `src/stories/`
3. **View in Storybook**: Run `npm run storybook` to see components in isolation
4. **Test Interactions**: Use Storybook addons to test component behavior
5. **Build & Deploy**: Deploy your Storybook documentation to GitHub Pages

## Learn More

### Storybook Documentation
- [Storybook for React](https://storybook.js.org/docs/react/get-started/introduction)
- [Writing Stories](https://storybook.js.org/docs/react/writing-stories/introduction)
- [Storybook Addons](https://storybook.js.org/docs/react/addons/introduction)

### React Documentation
- [Create React App Documentation](https://facebook.github.io/create-react-app/docs/getting-started)
- [React Documentation](https://reactjs.org/)

## Ejecting (Not Recommended)

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time with `npm run eject`. This command will remove the single build dependency from your project and copy all configuration files so you have full control over them.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments.

## License

This is a demo project for educational purposes.
