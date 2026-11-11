# ReSellit Lister demo: Full version · 6 marketplaces

Prebuilt static site (`site/`). Deploy this folder as its own Vercel project:

```
cd deploy/full
npx vercel deploy --prod
```

Or import the repo in Vercel and set **Root Directory** to `deploy/full`. No build step runs.

`vercel.json` marks every page `noindex`, allows same-origin framing (the demo's simulated browser uses iframes)
and rewrites marketplace listing URLs to the test-double listing page.

Source, tests and the full "measured vs not measured" section: see the README at the repo root.
