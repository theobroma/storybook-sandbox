# Storybook sandbox

## Links

[Usefull links](./docs/links.md)

## Quick Start

```bash
# Install dependencies
npm install

# Serve on localhost:3000
npm start

# Build for production
npm run build

# Format with prettier
npm run format

# Lint with eslint
npm run lint
```

## Deploy to Netlify

```bash
# Generate a production build and deploy it

  "scripts": {
    ...
    "predeploy": "npm run build",
    "deploy": "netlify deploy -p"
  },
```

### Status badge

[![Netlify Status](https://api.netlify.com/api/v1/badges/e5305ec2-b7f3-4150-9f4b-3e48763077f7/deploy-status)](https://app.netlify.com/sites/thirsty-swirles-283e34/deploys)
