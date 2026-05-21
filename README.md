# Thalk — Landing Page

Landing page for **Thalk**, a walking journal iOS app. Built with plain HTML and CSS — no frameworks, no build step.

## Files

| File | Purpose |
|---|---|
| `index.html` | Main landing page |
| `privacy.html` | Privacy policy |
| `styles.css` | Shared stylesheet for both pages |

## Preview locally

Open `index.html` directly in a browser:

```
open index.html
```

Or serve it with any static file server, for example:

```
npx serve .
```

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Set the source to the `main` branch, root folder.
4. The site will be live at `https://<your-username>.github.io/<repo-name>/`.

Once the app is live on the App Store, update the `href="#"` on the `.btn-appstore` link in `index.html` to the real App Store URL.
