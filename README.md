<div align="center">

# 📺 🎯 SonyLiv Live Events Auto-Sync

### by **Sayan Pal**

| 🌐 Live Website | [SonyLiv Live — Sayan](https://sayan-sonyliv-live.vercel.app/))  |

✨ A high-availability, fully automated data synchronization project ensuring the SonyLiv live events list is always fresh and reliable.

---

![Workflow Status](https://img.shields.io/github/actions/workflow/status/YOUR_USERNAME/YOUR_REPO/sync.yml?label=Workflow%20Status&style=for-the-badge&color=e8003d)
![Stars](https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO?style=for-the-badge&color=f4b400&label=Total%20Stars)
![Forks](https://img.shields.io/github/forks/YOUR_USERNAME/YOUR_REPO?style=for-the-badge&color=ff6b35&label=Total%20Forks)
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=YOUR_USERNAME.YOUR_REPO&style=for-the-badge&label=Total%20Visitors)
![Repo Size](https://img.shields.io/github/repo-size/YOUR_USERNAME/YOUR_REPO?style=for-the-badge&color=00e676&label=Repo%20Size)

</div>

---

## 🔗 Quick Attribution (Credit)

This automated service is based on data collected and maintained by others. Full credit goes to the original source:

| Detail | Link |
|--------|------|
| 📦 Original Source Repository | [drmlive/sliv-live-events](https://github.com/drmlive/sliv-live-events) |
| 🌐 Live Website | [SonyLiv Live — Sayan](https://sayan-sonyliv-live.vercel.app/)) |
| 💬 Telegram Channel | [@TestCricket18](https://t.me/TestCricket18) |

---

## 🎯 Core Synchronization Details

| Component | Detail | Setting |
|-----------|--------|---------|
| 📄 Data File | `sonyliv.json` | JSON Format |
| ⏱️ Sync Frequency | Every 60 Seconds | Auto-Poll |
| 🔄 Update Mode | Client-Side Fetch | Zero Backend |
| 📡 Data Source | `raw.githubusercontent.com` | Live Pull |
| 🎥 Stream Format | HLS / M3U8 | HLS.js Player |
| 🖼️ Thumbnail Proxy | `wsrv.nl` | CORS Bypass |
| 🔁 HLS Proxy Chain | 4 Fallback Proxies | Auto-Retry |

---

## ✨ Features

- ⚡ **Zero-maintenance** — no server, no cron job, no backend
- 🔄 **Auto-refresh** every 60 seconds — always shows latest events
- 🎥 **Built-in HLS player** — streams play directly in the browser
- 🔁 **HLS Proxy fallback** — auto-retries through 3 proxies if direct stream fails
- 📱 **Fully responsive** — works on mobile, tablet, and desktop
- 🖼️ **Smart thumbnails** — proxied through `wsrv.nl` to bypass hotlink blocking
- 🏷️ **Sport filter tabs** — filter by Cricket, Football, Golf, Tennis & more
- ⚽ 🏏 ⛳ **Multi-sport support** — all sports auto-detected from JSON
- 🔔 **Telegram popup** — one-time channel join prompt for visitors

---

## 🚀 How It Works

```
GitHub (drmlive/sliv-live-events)
        │
        │  raw.githubusercontent.com/...sonyliv.json
        ▼
  My Website (index.html)
        │
        ├─ Parses matches array
        ├─ Builds sport filter tabs dynamically
        ├─ Displays event cards with thumbnails
        ├─ Opens HLS player on click
        │     └─ Direct → Proxy 1 → Proxy 2 → Proxy 3
        └─ Auto-re-fetches every 60 seconds
```

---

## 📢 Use and Enjoy!

This project is your most reliable, **zero-maintenance** source for SonyLiv event data.

We encourage developers and enthusiasts to:

- ⭐ **Star** this repository to show appreciation
- 🍴 **Fork** it and build your own version
- 📦 **Integrate** the JSON into your own projects
- 📣 **Share** it with fellow sports fans!

> Hit the **⭐ Star** button to help Sayan keep this project running!

---

## 👤 Project Developed by

<div align="center">

**Sayan Pal**

[![Telegram](https://img.shields.io/badge/Telegram-Join%20Channel-2196F3?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/TestCricket18)

*Built with ❤️ for sports fans everywhere*

</div>

---

<div align="center">
<sub>Data sourced from <a href="https://github.com/drmlive/sliv-live-events">drmlive/sliv-live-events</a> · Site by Sayan Pal</sub>
</div>
