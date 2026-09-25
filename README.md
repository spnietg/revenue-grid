# Revenue Grid — wireframes

A static site. No build step, no dependencies, no server code.

## Deploy to Vercel (drag and drop)

1. Go to **vercel.com/new**
2. Drag this folder (or the zip) onto the page
3. Framework preset: **Other**. Leave build command and output directory empty.
4. Deploy.

Vercel gives you a `*.vercel.app` URL. Anyone with the link can open it — there
is no login. To restrict it, turn on Deployment Protection in the project settings.

## Structure

```
index.html            the eight screens, as cards
entry-grid.html       sales entry grid
manager-view.html     region view + end-of-day digest
projection-summary.html
client-tracking.html
coverage-accuracy.html
prs-insights.html     data checks + masters & lists
dashboard.html        leadership dashboard
delegation.html       transfer, cover and permissions
assets/dc-lite.js     the renderer the wireframes run on
assets/site.css
assets/site.js        board scaling, zoom and view tabs
vercel.json           clean URLs
```

Screens with two views carry a tab switcher above the board.

Fonts load from Google Fonts. If your network blocks that, the pages fall back
to the system font and still render correctly.
