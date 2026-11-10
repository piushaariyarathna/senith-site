# Senith Anuhas - portfolio

Static site (no build step). Files: index.html, site.json (all the text and links), portrait.webp, uploads/ (new images), netlify.toml.

## Deploy
1. GitHub: New repository (e.g. senith-site), then "uploading an existing file" and upload everything in this folder (including the uploads folder with .gitkeep). Commit.
2. Netlify: Add new site > Import an existing project > GitHub > pick the repo. Build command: empty. Publish directory: `.` Deploy.
3. GitHub token: Settings > Developer settings > Personal access tokens > Fine-grained tokens > Generate.
   Repository access: Only select repositories > your repo. Permissions > Contents: Read and write. Copy the token.
4. Open https://YOUR-SITE.netlify.app/#edit , tap "Edit site", open "Connect GitHub", fill repo (yourname/senith-site), branch (main), token.
5. Edit anything, press Save. Netlify redeploys in about a minute.

Only you see the Edit button (the page needs #edit in the address). The token is stored in that browser only. Use it on your own device and revoke it on GitHub if lost.
