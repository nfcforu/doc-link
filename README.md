# 🎯 CLEAN SIMPLE DEPLOYMENT

This folder contains ONLY what you need:
- index.html (patient booking)
- nurse.html (nurse dashboard)  
- dash.html (admin panel - password: fishta2021)
- wrangler.jsonc (deployment config)

## Deploy in 1 Step:

Open terminal in THIS folder and run:

```bash
npx wrangler deploy
```

That's it!

## What You'll Get:

URL like: `https://nfc-queue-project.YOUR-SUBDOMAIN.workers.dev`

Then access:
- `/dash.html` - Admin panel
- `/index.html?clinic=ID` - Patient booking
- `/nurse.html?clinic=ID` - Nurse dashboard

## If That Doesn't Work:

Try this command instead:

```bash
npx wrangler deploy --assets=.
```

## Still Issues?

Make sure you're logged in:

```bash
npx wrangler login
```

Then try deploying again.
