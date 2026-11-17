# aibcaoo

个人使用的 rclone Google Drive 授权配置说明网站，由 oenhu 维护。

A bilingual information website for a personal rclone Google Drive authorization setup, maintained by oenhu.

## Public pages

- Homepage: https://oenhu.github.io/MyRcloneSite/
- Privacy Policy: https://oenhu.github.io/MyRcloneSite/privacy.html
- Terms of Service: https://oenhu.github.io/MyRcloneSite/terms.html
- Contact: https://github.com/oenhu/MyRcloneSite/issues

## Hosting

Buildless HTML/CSS. GitHub Pages publishes `main` → `/ (root)`. `.nojekyll` disables Jekyll processing. No dependencies or build step. Preview with `python3 -m http.server 8765`.

## Google Auth Platform

Use the name **aibcaoo** and the three public page URLs above. The support email required by Google is configured in Google Cloud; no email is displayed on this website.

Brand verification also requires verified ownership of the relevant authorized domains using a Google account associated with the Cloud project. Publishing this website alone does not complete domain, brand or scope verification. A custom domain may be needed if Google cannot accept or verify the shared hosting subdomain. Do not enter `github.com` as a domain you own.

For Search Console URL-prefix verification, add Google's exact HTML verification file at the required path or its supplied meta tag in `index.html`; do not invent a verification token. The site does not currently include one.

Privacy content describes local rclone use with no developer backend. Update it before changing the application's actual data practices or scope. Do not put client secrets, tokens or private configuration in this repository.
