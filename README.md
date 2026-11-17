# Sakib Hosen — 3D Interactive Portfolio & Network Engineering Lab

Personal 3D WebGL portfolio website and interactive network engineering case studies hub for **Sakib Hosen** (**MD Sakib Hosen**), an **MTCNA** and **MTCRE** certified Network & Systems Support Engineer, hosted on GitHub Pages.

- **Live Portfolio (Primary 3D Edition):** [Sakib Hosen — Network & Systems Support Engineer](https://sakib-hosen-dev.github.io/)
- **Interactive Case Studies Hub:** [Technical Case Studies & Labs (`case-studies.html`)](https://sakib-hosen-dev.github.io/case-studies.html)
- **Legacy Portfolio (Canonicalized Archive):** [MD Sakib Hosen — Classic Portfolio](https://md-sakib-hosen.github.io/)

---

## Overview

This minimalist, performance-optimized static portfolio combines an interactive **3D WebGL Infinity ↔ Möbius** centerpiece with hands-on infrastructure case studies across MikroTik RouterOS v7 routing, OpenWrt 25.12.6 (`apk`) edge deployments, colocation data center operations, enterprise Windows administration, and workstation hardware diagnostics.

## Interactive Case Studies Hub (`case-studies.html`)

| Case Study | Direct Link | Highlights |
| :--- | :--- | :--- |
| **01. ISP Core & Failover** | [case-studies.html#mikrotik](https://www.google.com/search?q=https://sakib-hosen-dev.github.io/case-studies.html%23mikrotik) | Dual-WAN BGP/OSPF failover (`<30ms` BFD) simulator, FTTH PPPoE concentrator, 802.1Q VLAN isolation, interactive PCQ bandwidth calculator, and production RouterOS v7 CLI runbooks |
| **02. OpenWrt 25.12.6 (`apk`)** | [case-studies.html#openwrt](https://www.google.com/search?q=https://sakib-hosen-dev.github.io/case-studies.html%23openwrt) | ASUS RT-AX52 (MediaTek MT7981B, 234 MiB RAM) deployment with interactive Hardware Flow Offloading (HFO) vs. SQM CAKE toggle, Quad DoH (`5053–5056`), 480K+ OOM-safe AdBlock-Fast, One-Click Health Check, and ASUS TFTP Rescue |
| **03. Mobile Admin & Telemetry** | [case-studies.html#openwrt-mobile](https://www.google.com/search?q=https://sakib-hosen-dev.github.io/case-studies.html%23openwrt-mobile) | Smartphone-first management via Yet Another LuCI App, Argon Theme v2.4.3 Dark UI, OppsError404 suite (`/var/run/client_monitor` fix), `vnstat2`/`nlbwmon`/`collectd`, and LAN-isolated `ttyd` (`:7681`) & Prometheus (`:9100`) |
| **04. Hardware & Enterprise IT** | [case-studies.html#hardware](https://www.google.com/search?q=https://sakib-hosen-dev.github.io/case-studies.html%23hardware) | Custom workstation assembly, thermal burn-in diagnostics, Kernel-Power stability troubleshooting, and enterprise Windows administration |

## Main Portfolio Sections (`index.html`)

| Section | Highlights |
| :--- | :--- |
| **3D Portrait Hero (`#about`)** | Interactive 3D Infinity ↔ Möbius WebGL particle system, real suited portrait, and split `SAKIB` / `HOSEN` Name Particle Accelerator |
| **Executive Overview (`#overview`)** | Engineering summary, availability, and core infrastructure focus in Dhaka, Bangladesh |
| **Career Track (`#experience`)** | Lead Technical Trainer (**Earth Telecommunication Pvt. Ltd.** / Race Online Training Wing), Junior Network Engineer (**SSD Tech / Carnival Internet / Dotlines**), Data Center Operations Intern (**Dhaka Colo**), Hardware Engineer (**Master Technology Ltd**), and Apprenticeships |
| **Technical Case Studies (`#projects`)** | 4-row minimalist architectural cards linking directly into the interactive Case Studies Lab |
| **Core Capabilities (`#skills`)** | MikroTik & ISP Routing, OpenWrt Edge Systems, Enterprise Windows Support, Workstation Hardware, and Data Center Colocation |
| **Education & Accreditations (`#credentials`)** | Diploma in Engineering (CST), **MTCNA**, **MTCRE**, and Data Center Colocation Training |
| **Currently Enriching (`#learning`)** | Primary-phase upskilling in **Artificial Intelligence**, **Automation**, and **DaVinci Resolve & Video Editing** |
| **Direct Channels (`#contact`)** | Direct contact dispatch, downloadable CV (`MD_Sakib_Hosen_CV.pdf`), and verified social links |

## Tech Stack, Performance & SEO

- **3D & UI Architecture:** Semantic HTML5, Three.js WebGL Infinity/Möbius particle engine, Tailwind CSS, two-tier mobile/tablet navigation dock, `IntersectionObserver` off-screen WebGL pausing, `requestAnimationFrame`-throttled scroll handlers, and a live animated circular-portrait cyan-ring `<canvas>` favicon
- **Typography:** [Google Fonts](https://fonts.google.com/) (`Inter`, `Instrument Serif`, `JetBrains Mono`) and `Sakana` display typography
- **Security & PWA:** `.nojekyll` static serving bypass, custom `404.html` (`noindex, follow`), and `manifest.json`
- **SEO & Delayed 4-Engine Analytics:** Schema.org JSON-LD (`WebSite`, `ProfilePage`, `CollectionPage`, `Person` with `alternateName` aliases), `sitemap.xml`, `robots.txt`, IndexNow (`8f4e2a9c1b7d6e3f5a0c9b8e7d6c5b4a.txt`), Google Search Console (`google4b39a84a97f42e38.html`), Bing Webmaster (`BingSiteAuth.xml`), Yandex verification, plus interaction-deferred Google Analytics 4 (`G-8CWWDLVF2R`), Ahrefs Web Analytics, Microsoft Clarity, and Cloudflare Web Analytics
- **Hosting:** [GitHub Pages](https://pages.github.com/) (`sakib-hosen-dev.github.io`)

## Repository Structure

```text
sakib-hosen-dev.github.io/
├── .nojekyll                              # Disables Jekyll for instant static serving
├── index.html                             # Main 3D WebGL portfolio (~365 KB)
├── case-studies.html                      # Unified interactive case studies hub
├── 404.html                               # Branded dark-mode fallback page
├── manifest.json                          # PWA web app manifest
├── sitemap.xml                            # XML sitemap for search engines
├── robots.txt                             # Crawler & sitemap directives
├── favicon.ico                            # Multi-size portrait favicon fallback
├── google4b39a84a97f42e38.html            # Google Search Console verification
├── BingSiteAuth.xml                       # Bing Webmaster Tools verification
├── 8f4e2a9c1b7d6e3f5a0c9b8e7d6c5b4a.txt   # IndexNow verification key
├── MD_Sakib_Hosen_CV.pdf                  # Downloadable executive CV
├── README.md                              # Repository documentation
└── assets/
    ├── apple-touch-icon.png               # 180x180 iOS home screen icon
    ├── favicon.png                        # 192x192 circular cyan-ring portrait favicon
    ├── favicon.svg                        # Scalable SVG portrait favicon
    ├── og-image.jpg                       # 1200x630 editorial split Open Graph card
    └── profile-sakib.jpg                  # Suited studio portrait
```

## Local Preview

Since this is a static site with no build step required, you can preview it locally with any HTTP server:

```bash
git clone https://github.com/sakib-hosen-dev/sakib-hosen-dev.github.io.git
cd sakib-hosen-dev.github.io
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Connect

- **Portfolio (New 3D Edition):** [sakib-hosen-dev.github.io](https://sakib-hosen-dev.github.io/)
- **Portfolio (Legacy):** [md-sakib-hosen.github.io](https://md-sakib-hosen.github.io/)
- **Case Studies Hub (New):** [sakib-hosen-dev.github.io/case-studies.html](https://sakib-hosen-dev.github.io/case-studies.html)
- **Case Studies Hub (Legacy):** [md-sakib-hosen.github.io/case-studies.html](https://md-sakib-hosen.github.io/case-studies.html)
- **GitHub Organization:** [github.com/sakib-hosen-dev](https://github.com/sakib-hosen-dev)
- **LinkedIn:** [linkedin.com/in/zero-sakib](https://www.linkedin.com/in/zero-sakib/)
- **GitHub:** [github.com/Md-Sakib-Hosen](https://github.com/Md-Sakib-Hosen)
- **X (Twitter):** [@iam\_sakib\_hosen](https://x.com/iam_sakib_hosen)
- **Telegram:** [@zero_mh_sakib](https://t.me/zero_mh_sakib)
- **Facebook:** [facebook.com/zero.mh.sakib](https://facebook.com/zero.mh.sakib)
- **Email:** [md.sakibhosen003@gmail.com](mailto:md.sakibhosen003@gmail.com)
