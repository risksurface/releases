# RiskSurface Releases

Welcome to the **official release repository** for **RiskSurface**.

This repository is the trusted distribution point for all publicly available RiskSurface releases.

## Purpose

This repository contains:

* Official release binaries
* Signed release artifacts
* Release manifests
* SHA-256 checksums
* Digital signatures
* Release notes

The Update Center built into RiskSurface uses this repository to discover and download product updates.

## Available Artifacts

Each release may include platform-specific packages such as:

* Linux (amd64, arm64)
* Windows (amd64)
* macOS (Apple Silicon & Intel)
* Docker packages (where applicable)

Along with:

* `release.json`
* `checksums.txt`
* `checksums.sig`

## Integrity Verification

Every release is cryptographically signed.

Before installing an update, RiskSurface automatically verifies:

* Digital signature
* SHA-256 checksum
* Package integrity

This helps ensure that downloaded artifacts are authentic and have not been modified.

## Release Channels

RiskSurface supports multiple release channels.

| Channel | Description                         |
| ------- | ----------------------------------- |
| Stable  | Production-ready releases           |
| Beta    | Preview releases for testing        |
| RC      | Release candidates                  |
| Nightly | Development builds (when available) |

The Update Center automatically selects the appropriate channel based on your product configuration and license.

## Automatic Updates

Self-hosted installations can periodically check this repository for new releases using the built-in Update Center.

Administrators can configure:

* Update channel
* Automatic or manual downloads
* Scheduled update checks
* Offline update bundles (Enterprise)

## Air-Gapped Environments

For customers operating in disconnected environments:

1. Download the required release assets from this repository.
2. Verify the included checksums and signatures.
3. Import the release package using the RiskSurface Update Center.

## Source Code

This repository does **not** contain the RiskSurface source code.

It is dedicated solely to distributing official release artifacts.

## Security

If you believe you have identified a security issue related to RiskSurface, please report it responsibly through our security disclosure process instead of opening a public issue.

## License

The binaries distributed through this repository are subject to the applicable RiskSurface End User License Agreement (EULA) and your active subscription or license terms.

Downloading a release does not grant permission to use the software beyond the rights provided by your license.

## Support

For product documentation, licensing, enterprise support, or customer assistance, please visit the official RiskSurface website and customer portal.
