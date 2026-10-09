# Rim Zouari — Portfolio

Single-page static portfolio site (no build step — plain HTML/CSS/JS).

## Run locally

Open `index.html` directly in a browser, or serve it:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy

This repo includes a [`render.yaml`](render.yaml) that configures a Render **Static Site**
service (`rim-zouari-portfolio`) serving the repo root with no build command.

1. Push this repo to GitLab (see below).
2. On [Render](https://dashboard.render.com), **New +** → **Blueprint**, connect your GitLab
   account, and select this repository. Render reads `render.yaml` and creates the static site
   automatically.
3. Once deployed, Render gives you a URL like `https://rim-zouari-portfolio.onrender.com`
   (a custom domain can be attached later from the service's **Settings** tab).

Any push to the connected branch redeploys automatically.
