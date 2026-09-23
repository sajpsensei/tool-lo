# Tool Lỏ public website

Static public pages used by the Chrome Web Store listing and Google OAuth branding.

## Files

- `index.html`: application home page.
- `privacy.html`: public privacy policy.
- `terms.html`: terms of service.
- `styles.css`: shared responsive styles.

## GitHub Pages deployment

1. Create a public repository named `tool-lo`.
2. Upload the four runtime files in this folder to the repository root.
3. In repository **Settings → Pages**, deploy from the `main` branch and `/ (root)`.
4. Verify the resulting `https://<username>.github.io/tool-lo/` site in Google Search Console.
5. Add `<username>.github.io` to Google Auth Platform **Authorized domains**.
6. Use these OAuth Branding URLs:
   - Home: `https://<username>.github.io/tool-lo/`
   - Privacy: `https://<username>.github.io/tool-lo/privacy.html`
   - Terms: `https://<username>.github.io/tool-lo/terms.html`

Do not add a logo to OAuth Branding until brand verification is intentionally requested.
