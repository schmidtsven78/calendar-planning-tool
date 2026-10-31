# Calendar Planning - web tool 2026

> **Calendar Planning is a browser-based planning utility that surfaces races which are open right now, helping you build schedules around the availability that actually exists.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/schmidtsven78/calendar-planning-tool?style=flat-square)](https://github.com/schmidtsven78/calendar-planning-tool)

---

<p align="center">
  <a href="https://schmidtsven78.github.io/calendar-planning-tool/">
    <img src="https://img.shields.io/badge/Download-Calendar%20Planning%20Latest-brightgreen?style=for-the-badge" alt="Download Calendar Planning">
  </a>
</p>

> **[Direct Download - Calendar Planning v](https://schmidtsven78.github.io/calendar-planning-tool/)**

---

[Download Latest Build](https://schmidtsven78.github.io/calendar-planning-tool/)

---

## About Calendar Planning

Calendar Planning gives you a quick read on which races can be scheduled at the moment. Instead of digging through entries that are already closed off, you get a focused view of what remains open, which makes calendar decisions faster and less error-prone.

The whole tool lives in the browser, so there is nothing to install locally and no desktop package to manage. Open it, scan the available races, and move on with your planning. That makes it a practical fit for anyone who wants a lightweight check on race availability without extra setup.

---

## Features

- Runs entirely in the browser, no desktop install needed
- Shows the races that are open for planning right now
- Lets you build schedules around current availability
- Compact layout built for quick scanning
- Fits into calendar-driven planning workflows
- Keeps open races clearly separated from unavailable ones
- Straightforward access model with no packaging step
- Optimized for fast visual review of planning options

---

## Installation

Grab the repository by cloning or downloading it, then open the web project in a browser or serve it through any static file host.

Example:

```bash
git clone https://github.com/schmidtsven78/calendar-planning-tool.git
cd REPO
```

Once cloned, start the HTML entry point from a local web server, or open the main page directly in your browser if your setup allows it.

---

## Usage

1. Launch the application in a browser.
2. Look over the races currently listed as available.
3. Plan around the open slots shown in the list.
4. Reload the page whenever availability changes.

If you host it locally, refresh after editing source files so the newest planning data shows up.

---

## Configuration

Settings are expected to live either in the web project files or in the data source that supplies the displayed races. To change what the planner shows, edit the HTML content or the related static data behind the interface.

Example structure:

```json
{
  "calendar": "planning",
  "view": "available-races",
  "source": "local-or-hosted-static-data"
}
```

---

## Requirements

- A current web browser
- HTML support
- A local web server if you would rather not open files directly
- Sufficient storage for the repository files and any planning data you add

---

## FAQ

**How do I get the latest version?**  
Use the download link above, or pull the newest changes from the repository.

**Where do I edit the schedule data?**  
Look at the project files that drive the HTML content or the static data source the planner reads from.

**What if the page stays empty?**  
Confirm the browser can load the project files, and check that the availability data exists and is formatted correctly.

**Do I need to install anything?**  
No. It is a web tool, so you can open it in a browser and use it as a browser-based planning interface.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
