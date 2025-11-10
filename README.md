# World Time Finder

A React + Tailwind + Luxon app that lets users search a city, view its local and UK time, and convert times between both.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Deploy to Vercel

1. Push this folder to a new GitHub repository.
2. Go to [Vercel](https://vercel.com/), import your GitHub repo.
3. Vercel auto-detects a Vite project. Use default settings (`npm run build`, output `dist`).
4. Click **Deploy** and get your live link.

## Notes

- Uses GeoDB Cities API (no key needed) for city suggestions.
- Uses Open-Meteo for timezone data.
- Uses Luxon for accurate time conversions with DST handling.
