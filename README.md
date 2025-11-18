# Companies Directory — Frontend

A small, extensible React app demonstrating: data fetching, filters, sorting, pagination, Tailwind styling, and good UX states (loading/error). The API is mocked via `public/companies.json`.

## Run locally

1. Install dependencies

```bash
npm install
```

2. Start dev server

```bash
npm run dev
```

Open http://localhost:5173 (Vite default) and explore.

## Deploy to Netlify / Vercel

- Build: `npm run build`.
- Point the deploy to the repository root. For Netlify, set build command `npm run build` and publish directory `dist`.

## Video recording tips (2–3 minutes)

1. Start with a 20–30s intro: your name, role applied for, and what the project does.
2. Explain folder structure and where critical logic lives (FiltersContext, useFetchCompanies, CompanyTable).
3. Demonstrate the app: searching, filtering, sorting, pagination, and show loading/error states.
4. Mention any trade-offs and future improvements (e.g., server-side pagination, caching, tests).

## Extensions / Next steps

- Replace mock API with Node/Express + MongoDB for dynamic data.
- Add unit tests (Jest + React Testing Library).
- Add infinite scroll instead of pagination.
- Add accessibility audits and keyboard navigation.
