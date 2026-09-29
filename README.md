# Quest downloads

Official signed Quest downloads for the Apple Silicon Mac closed beta.

[Download the latest approved release](https://github.com/steenfatt/quest-releases/releases/latest). A candidate becomes available here only after approval; until the first approval, no download is available.

Each release lists its version, macOS requirement, and checksums. Check that release's macOS requirement before installing.

## Install and update

1. Download the DMG from the approved release.
2. Open the DMG and drag Quest into Applications.
3. Open Quest from Applications.

Updates are manual: quit Quest and install the newer approved signed package, replacing the application in Applications. Your app data is preserved.

## Verify a download

Download the version's assets and `SHA256SUMS.txt` into the same folder. In that folder, run:

```sh
shasum -a 256 -c SHA256SUMS.txt
```

Use the checksum file from the same version as the downloaded assets.

## Release selection

Beta versions use GitHub's regular-release setting so the latest-release link selects the approved download. They remain closed-beta builds.

Published versions appear in [Releases](https://github.com/steenfatt/quest-releases/releases). The release operator selects a compatible previous version when needed; Quest does not automatically downgrade. Install an older version only when directed by the operator.
