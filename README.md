# RS Games Client — Downloads

This repo hosts distributable binaries for the **RS Games Client**, the
accessible multiplayer desktop client for [rsgames.org](https://www.rsgames.org).

The client source code lives in a private repo. This repo exists only
to host downloads on GitHub's CDN with public, unauthenticated access.

## Get the latest version

Visit the [**Releases page**](https://github.com/rsgames-zgp/rsgames-client-releases/releases/latest)
and download the file matching your platform:

| Platform | File |
|---|---|
| **Windows** | `rsg-windows-x86_64.zip` |
| **macOS (Apple Silicon — M1/M2/M3/M4)** | `rsg-mac-arm64.zip` |
| **macOS (Intel)** | `rsg-mac-x86_64.zip` |
| **Linux x86_64** | `rsg-linux-x86_64.tar.gz` |

## Beta builds

Want to test upcoming changes before they ship? The [Releases page](https://github.com/rsgames-zgp/rsgames-client-releases/releases)
also lists prereleases tagged `vX.Y-beta-N` — those are automatic builds from
the development channel. Bugs welcome at [rsgames@gmail.com](mailto:rsgames@gmail.com).

## Reporting bugs

Email [rsgames@gmail.com](mailto:rsgames@gmail.com) — please include:
- Your operating system + version
- Which client release you downloaded
- What you were doing when the bug happened
- Anything that appeared in the `errors.log` file (location varies by OS — your app-data dir)

## Why is the source private?

Historical reasons + we're not currently set up to review external contributions.
Once the codebase is in better shape we may flip the source repo public too.
