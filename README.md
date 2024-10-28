# Vite React Docker Setup

A React application built with Vite and pnpm, using multi-stage Docker builds. The application is served using `serve` package on port 3000.

## Quick Start

### Build Docker Image

```
docker build -t vite-react-app .
```

### Run Container

```
docker run -d -p 3000:3000 vite-react-app
```

The application will be available at `http://localhost:3000`
