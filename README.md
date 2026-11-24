# A Little World for Munchii ?

A responsive scrapbook for a first monthsary, built with React, TypeScript, Vite, Tailwind CSS, Framer Motion, and Lucide icons.

## Run it

```sh
npm install
npm run dev
```

Create a production bundle with `npm run build`; preview it with `npm run preview`. The included `vercel.json` serves the Vite single-page app on Vercel.

## Personalize the memories

Edit `src/memories.ts` to change each caption, description, category, date, or image path. Add photos to `public/images/memories/`, then add an entry to the `memories` array. The supplied JPEGs and MP4 are already copied there. Replace the hero photo path in `src/App.tsx` if you want another image on the cover.

The optional music player looks for `public/music/our-song.mp3`. Add your own audio file at that path to enable it; music never autoplays.

The relationship milestones are in the `timeline` array in `src/memories.ts`. Update the letter text directly in the letter section in `src/App.tsx`.
