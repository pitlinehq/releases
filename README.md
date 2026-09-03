# Pitline binaries

Public downloads for the Pitline client. **Source is not in this repository.** Product source lives in the private `pitlinehq/pitline` repo.

## What this is

On each version tag, we publish:

- `pitline-installer.sh`
- `.tar.gz` archives for Linux (gnu/musl, x86_64 and arm64) and macOS (Intel and Apple Silicon)

There are no GitHub Releases here yet. The first tag will populate them.

## Install

Instructions: [pitline.dev/install.html](https://pitline.dev/install.html)

```sh
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/pitlinehq/releases/releases/latest/download/pitline-installer.sh | sh
pitline install-service
```

The client is fully local: no analytics, telemetry, or other data collection by Pitline Inc. Website analytics on pitline.dev are separate and are not in this software.

## Not included

- Homebrew tap (not created yet)
- App Store / iOS
- Signed/notarized macOS builds until the Pitline Inc. Apple Developer org is approved
