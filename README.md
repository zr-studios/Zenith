# Zenith

A supercharged, single-file project built for speed, utility, and intelligence. 

Zenith is a unified ecosystem engineered by fusing the elite capabilities of **HORIZON** and **NLGEP**. Rather than attempting to replace either framework, Zenith bridges the gap—extracting HORIZON's robust routing resilience and marrying it to NLGEP’s dynamic logic processing. The result is a lightweight, zero-bloat environment containing a self-contained AI module, an on-demand gaming suite, and a high-performance proxy engine packed into a single script.

---

## System Architecture Overview

Because Zenith runs entirely out of a single file, it utilizes a highly decoupled, asynchronous architecture to prevent thread-blocking between its core modules:


---

## Deep Dive: Core Pillars


## Core Features

* **Wasm-Driven Proxy Engine:** Inherited from HORIZON. Uses `libcurl.js` compiled to WebAssembly running over the WISP protocol instead of Service Workers—making it entirely immune to standard URL blocklists and extension filters.
* **Stream & Game Optimization:** Built using NLGEP's data-splitting layer. Large multimedia assets and heavy multiplayer web games load in fragmented sections to bypass strict memory limits and drop latency.
* **Intelligent Client-Side AI:** An integrated companion interface providing offline automation tools, contextual logic assistance, and automatic proxy fallback configurations.
* **100% Single-File Portability:** Zero dependencies, zero build steps, and zero server architecture. Everything runs smoothly inside a single `.html` document.

### 2. High-Velocity Proxy Engine
Built directly upon HORIZON’s networking framework, the native proxy engine gives users complete web freedom and security.
* **Stealth Routing:** Automatically strips identifying HTTP request headers, replaces user-agents, and bypasses standard restrictive firewalls.
* **Smart Traffic Splitting:** Offloads heavy media requests locally while securely tunneling restricted traffic through the proxy core.

### 3. Native Mini-Game Suite
A dedicated playground layer built right into the architecture for downtime or testing interaction responsiveness.
* **No-Asset Rendering:** Games are delivered utilizing text-based matrices, inline canvas components, or lightweight mathematical rendering, requiring exactly zero external image or audio files.
* **Low Latency:** Runs directly on the main event loop's tick system with negligible CPU footprint.

---

## Why Single-File?

* **Portability:** Move your entire suite anywhere via a single copy-paste, curl command, or file transfer.
* **Zero Configuration Hell:** No intricate folder mappings, broken symlinks, or missing companion assets. 
* **Instant Deployment:** Ideal for sandboxed environments, restricted servers, or minimal system overhead containers.
* **Portability:** Move your entire suite anywhere via a single copy-paste, curl command, or file transfer.
* **Zero Configuration Hell:** No intricate folder mappings, broken symlinks, or missing companion assets. 
* **Instant Deployment:** Ideal for sandboxed environments, restricted servers, or minimal system overhead containers.

* # Zenith

A supercharged, single-file static powerhouse featuring intelligent web proxying, native cloud-free games, an embedded AI assistant, and zero-setup deployment. 

Zenith is a unified client-side browser environment created by fusing the networking resilience of **HORIZON** and the performance-optimized entertainment engine of **NLGEP**. Rather than trying to replace either, Zenith blends their strengths: extracting HORIZON's unblockable WebAssembly-driven network tunneling and marrying it to NLGEP's dynamic media streaming architecture and low-latency gaming framework. 

---

## Getting Started & Deployment

Because Zenith is a static application, you don't need a terminal, Node.js, or complex configurations to run it. You can deploy it using any of the options below:

### Option 1: Local Execution (Unblockable)
1. Download the `index.html` file (or clone this repository).
2. Double-click the file to open it directly in your browser as a local file (`file://`).
3. *Network filters cannot trace or block local files, ensuring complete web freedom.*

### Option 2: Host Anywhere Static Files Work
Drop the single `index.html` file into any free cloud static hosting platform. It works flawlessly out-of-the-box on:
* **GitHub Pages** / **Vercel** / **Netlify** / **Cloudflare Pages**
* **Google Sites** or embedded natively inside an `about:blank` iframe link.

### Option 3: Copy-Paste HTML Runners
Open the file in a text editor, copy all of the source code (`Ctrl + A`), and paste it directly into any browser-based WYSIWYG HTML widget runner or sandbox.

---

## Credits & Framework Lineage

Zenith is proudly built on the backs of giants in the open-source privacy community. Deep gratitude and credit go out to:
* **RiptideMC (HORIZON):** For the hardened browser UX infrastructure, stealth routing, and anti-telemetry baselines.
* **WhyAlllOfThemTaken (NLGEP):** For the optimized game-handling, streaming performance layers, and strict site fallback settings.
* **Nautilus Labs / OS (GUST):** For the legendary foundational proxy engine design and original UI paradigms.
* **Mercury Workshop:** For pioneering the WISP network protocols and WebAssembly connection bridges.

---

## License

This project is open-source software licensed under the **AGPL-3.0 License** - see the [LICENSE](LICENSE) file for more details. In alignment with open-source guidelines, please preserve the credit chain for GUST, HORIZON, and NLGEP in your downstream distribution layouts!
