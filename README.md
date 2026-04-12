# Morphe Releases

Public distribution repository for Morphe patched APK releases.

This repository is intended for:

- GitHub Releases containing patched APK assets and build metadata
- Obtainium import metadata at `config/obtainium-import.json`

Obtainium import URL:

- `https://raw.githubusercontent.com/qudditch/Morphe-Releases/main/config/obtainium-import.json`

Notes:

- Release assets are published automatically from the private build repository.
- Release tags are versioned rather than overwritten in place.
- Because some releases may contain only the apps that changed, Obtainium should keep `fallbackToOlderReleases=true`.
