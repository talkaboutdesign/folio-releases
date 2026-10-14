# Folio releases

> [!WARNING]
> **Folio is in alpha.** Expect bugs, missing features and breaking changes, including to the file format,
> between versions. Keep your `.folio` files in git or backed up.

This repository only hosts the Folio desktop app's installers and update files. There is no source code here.

## Install (macOS)

1. Open the newest release on the [releases page](https://github.com/talkaboutdesign/folio-releases/releases).
2. Download `Folio-<version>-mac-arm64.dmg` (Apple Silicon) or `Folio-<version>-mac-x64.dmg` (Intel).
3. Open it and drag Folio to Applications.

Builds are signed and notarized. Folio updates itself: it checks for new builds in the background and asks before
restarting.

## Channels

- **Nightly** (`vX.Y.Z-nightly.<timestamp>`, prereleases): built from every change to Folio's `main` branch.
- **Stable**: coming later.

Windows builds are coming later.
