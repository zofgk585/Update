# Update

Update channel for the **server** Android app.

- `public/version.json` is served by Cloudflare Pages (build output directory: `public`).
- Publishing a GitHub Release with tag `vX.Y.Z` and asset `server-X.Y.Z.apk` runs the workflow, which rewrites `public/version.json` (versionCode = X*10000 + Y*100 + Z).
