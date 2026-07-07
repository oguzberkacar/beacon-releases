<div align="center">

# 🐚 Beacon

### Run all your local dev servers from the macOS menu bar.

Beacon lives in your menu bar and turns the mess of a dozen `npm run dev` tabs
into one calm panel. See what's running, on which port, and its live logs —
start, stop, and jump to any project in a click.

**[⬇︎ Download for macOS](https://github.com/oguzberkacar/beacon-releases/releases/latest)**  ·  Apple Silicon · signed & notarized · auto-updates

<br>

<img src="media/popover.png" alt="Beacon popover" width="380">

</div>

<br>

## Why Beacon

If you juggle several projects, you know the pain: terminal tabs everywhere, no
idea which server is still up, hunting for the port a dev server picked. Beacon
puts every project's commands one click away and shows their live state at a
glance — the menu-bar icon itself glows green while something runs.

## Features

- **Active at a glance** — every running command surfaces in one list, newest
  first, with its detected URL. Green = running, amber = starting, red = error.
- **Favorites** — star the commands you reach for most and keep them on top.
- **Folder groups** — bucket projects into folders (web, services, …) that
  collapse and remember their state.
- **Pin any command to the menu bar** — give a command its own menu-bar item
  for one-click start/stop and a live log tail, independent of the main popover.
- **Stop all** — kill every running process at once, with a checklist so you can
  spare the ones you want to keep.
- **Git at a glance** — branch and ahead/behind counts right on each project.
- **Built-in terminal** — a tabbed terminal with a project sidebar, no extra app.
- **One-click AI fix** — when a command errors, repair it with an AI assistant.
- **Auto port detection** — Beacon reads the `localhost:PORT` from a dev
  server's output and gives you a click-to-open link.
- **Package manager aware** — detects `yarn` / `pnpm` / `bun` / `npm` from the
  lockfile automatically.

<div align="center">
<img src="media/pinned-command.png" alt="A command pinned as its own menu-bar item" width="440">
<br>
<sub>Any command can become its own menu-bar item — status, controls, and live output.</sub>
</div>

## Install

1. **[Download the latest `.dmg`](https://github.com/oguzberkacar/beacon-releases/releases/latest)**
2. Open it and drag **Beacon** to your Applications folder.
3. Launch it — the lighthouse appears in your menu bar. Click it to open the popover.

The app is signed with a Developer ID and notarized by Apple, so it opens
without Gatekeeper warnings. After the first install, **updates arrive
automatically** — Beacon checks in the background and offers a one-click restart
when a new version is ready.

## Requirements

- macOS 11 (Big Sur) or later
- Apple Silicon (M1 or newer)

## Updates

Beacon updates itself. It checks for a new release on launch and periodically
while running; when one is downloaded it shows a notification and installs on the
next restart. You can also trigger a check from the menu-bar menu → **Check for
Updates…**

---

<div align="center">
<sub>Beacon · a menu-bar launcher for developers who run a lot of servers.</sub>
</div>
