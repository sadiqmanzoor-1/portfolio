# SADIQ® — Portfolio

A one-page portfolio site for a web designer specializing in landing pages,
websites and Shopify design. Built as a single `index.html` — all CSS lives
inside the file, no frameworks, no build tools, no JavaScript.

## Preview locally

**Easiest:** double-click `index.html` — it opens and works in any browser.

**Better (auto-reloads on save):** in VS Code, install the **Live Server**
extension, then right-click `index.html` → **Open with Live Server**.

## Deploy to GitHub Pages (free hosting)

1. Create a new repository on [github.com](https://github.com/new) — for a
   personal-site URL, name it `<your-username>.github.io`; any other name
   works too (the URL just gets a suffix, see step 5).

2. Push this folder to it (run from this folder):

   ```bash
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git branch -M main
   git push -u origin main
   ```

3. On GitHub, open the repo → **Settings** → **Pages** (left sidebar).

4. Under **Build and deployment**, set **Source** to *Deploy from a branch*,
   pick branch **main** and folder **/ (root)**, then click **Save**.

5. Wait a minute or two, then visit:
   - `https://<your-username>.github.io/` if the repo is named `<your-username>.github.io`
   - `https://<your-username>.github.io/<repo-name>/` otherwise

   The Pages settings screen shows the exact URL once it's live.

Every future `git push` to `main` redeploys the site automatically.

## Customizing

- **Colors & fonts** — everything is defined once as CSS variables at the top
  of the `<style>` block in `index.html` (look for `:root`).
- **Email** — the Contact section's button links to
  `sadiqmanzoor.businness@gmail.com`; search for that string to change it.
- **Social links** — the footer's GitHub link is live; LinkedIn and Dribbble
  are still `href="#"` placeholders — swap in the real profile URLs.
