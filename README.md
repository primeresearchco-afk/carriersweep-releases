# CarrierSweep — downloads

CarrierSweep reads your insurance carrier portals every morning and tells you what changed. This repo only holds the installers and the small file the app reads to know when a newer build is out.

**Get it from the site: https://carriersweep.vercel.app** (setup guide: https://carriersweep.vercel.app/install)

Direct links, always the newest build:

- Apple Silicon (M1–M4): https://github.com/primeresearchco-afk/carriersweep-releases/releases/latest/download/CarrierSweep-mac-arm64.dmg
- Intel Mac: https://github.com/primeresearchco-afk/carriersweep-releases/releases/latest/download/CarrierSweep-mac-intel.dmg

`latest.json` is the update feed the installed app checks. Don't edit it by hand; `build/release.sh` in the app repo writes it.
