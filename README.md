This project is referred to https://fireship.io/lessons/redis-nextjs/
Youtube course link: https://www.youtube.com/watch?v=DOIWQddRD5M

## Set up Redis host link
Add REDIS_URL=redis://default:PASSWORD@HOST:PORT in .env.local

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Search cars
- Use CarForm to create some cars.
- Call createIndex in http://localhost:3000/api/createIndex and observer OK
- Use SearchForm to search created cars.
