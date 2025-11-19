Weekend dla kobiet - GitHub Pages + Decap CMS (OAuth)

Repository name: weekend-dla-kobiet
GitHub Pages URL: https://szymonkluba.github.io/weekend-dla-kobiet/

1) Create repository 'weekend-dla-kobiet' and push these files.
2) Enable GitHub Pages in repo settings (branch 'main' root).
3) Create GitHub OAuth App:
   - Homepage: https://szymonkluba.github.io/weekend-dla-kobiet/
   - Authorization callback: https://szymonkluba.github.io/weekend-dla-kobiet/admin/auth.html
   - Copy Client ID/Secret.

4) To use OAuth implicit flow:
   - In admin/config.yml you may need to set client_id. Some setups require adding client_id to Netlify CMS initializer.
   - Alternatively, you can add a script in admin/index.html to set CMS config with client_id.

5) Visit /admin to login. Authorize app and you'll be redirected to /admin/auth.html which stores token and returns to admin.

Notes:
- uploads/ is media folder.
- content.json holds site content.
