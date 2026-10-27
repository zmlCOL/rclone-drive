# hfdownload · Personal rclone Drive app

Static homepage and privacy policy for zmlCOL's personal Google Drive OAuth application, used with rclone on owner-controlled devices.

- Homepage: https://zmlcol.github.io/rclone-drive/
- Privacy policy: https://zmlcol.github.io/rclone-drive/privacy.html
- Hosting: GitHub Pages, `main` branch, repository root
- No build step, dependencies, application backend or analytics

This repository contains public informational pages only. Never commit OAuth tokens, client secrets, rclone configuration files or private user data.

This application is independently maintained and is not an official Google or rclone product. For personal use, Google OAuth production publishing and OAuth verification are separate. Production status removes the testing-specific seven-day refresh-token limit for newly issued tokens, but does not guarantee a token will remain valid forever. Existing rclone connections should be reauthorized after production publishing.
