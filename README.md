# doc-upload

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

## Docker: Build and Run Instructions

1. Build the Docker Image
```
docker build -t doc-upload:1.0 .
```
2. Run the Docker Container
```
docker run -p 8080:8080 doc-upload:1.0
```
Access the application at: http://localhost:8080
