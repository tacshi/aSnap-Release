<div align="center">

<img src="assets/aSnap.png" width="128" alt="aSnap logo">

# aSnap

**A fast, lightweight screenshot tool for macOS and Windows.**

Capture regions, scrolling pages, and full screens — then annotate,
OCR, pin, record, and share, all without leaving your keyboard.

[![Latest release](https://img.shields.io/github/v/release/tacshi/aSnap-Release?label=release)](https://github.com/tacshi/aSnap-Release/releases/latest)
[![Latest preview](https://img.shields.io/github/v/release/tacshi/aSnap-Release?include_prereleases&label=preview)](https://github.com/tacshi/aSnap-Release/releases)
[![Downloads](https://img.shields.io/github/downloads/tacshi/aSnap-Release/total)](https://github.com/tacshi/aSnap-Release/releases)

</div>

## Releases and previews

aSnap ships on two channels from the
[Releases page](https://github.com/tacshi/aSnap-Release/releases):

- **Releases** (tagged `vX.Y.Z`, marked *Latest*) are stable builds with no
  time limit.
- **Previews** (tagged `preview-…`, marked *Pre-release*) bring new features
  early. Each preview is valid for **180 days** from its build date; the exact
  date is in its release notes.

When a preview reaches the end of its window, screenshot capture is paused:

- ✅ Ink, laser pointer, and pinned images keep working
- ✅ Your capture history stays accessible — open, copy, save, and pin
  earlier screenshots at any time
- ⛔ New captures (region, scroll, full screen, OCR) are paused

Installing a newer preview or a release picks up right where you left off.
Previews show a notice in the tray menu when a newer build is available,
including the final release of the version you are previewing. On Windows,
previews can download, verify, and install the update for you.

## Install

### macOS

1. Download a `.dmg` from the
   [latest release](https://github.com/tacshi/aSnap-Release/releases/latest):
   - `-universal.dmg` — any Mac
   - `-arm64.dmg` — Apple Silicon (smaller)
   - `-x64.dmg` — Intel (smaller)
2. Open it and drag **aSnap** into **Applications**.
3. Launch aSnap from Applications — it appears in your menu bar.

On first use, macOS will prompt for **Screen Recording** and
**Accessibility** permissions (System Settings → Privacy & Security).

**Requirements:** macOS 12 or later, Apple Silicon or Intel.

### Windows

1. Download `…-windows-x64-setup.exe` from the
   [latest release](https://github.com/tacshi/aSnap-Release/releases/latest).
2. Run it. Installing a newer version upgrades an existing install in place.
3. aSnap starts in the system tray.

**Requirements:** Windows 10 version 2004 or later, x64.

## Highlights

Shortcuts are ⌘⇧ on macOS and Ctrl+Shift on Windows, and can be changed in
Settings.

- **Capture modes** — Region (1) with window/element snapping, Scroll (2)
  that auto-scrolls and stitches long content, Full Screen (3), and Pin (P)
  to float a screenshot above all windows
- **Region selection** — freeform drag or auto-snap to windows and UI
  elements, resize handles, and a 10x magnifier loupe with pixel
  coordinates
- **Annotations** — shapes, arrows, freehand pencil and marker, mosaic
  (pixelate/blur) redaction, number stamps, and text, with undo/redo
- **OCR & QR** (O) — extract text from screenshots and copy it instantly;
  QR codes are auto-detected and one click copies their contents
- **Screen recording** (R) — record the screen and export the result
- **Screen presentation** — draw on screen with Ink (D) or point with the
  Laser (E) during demos and calls
- **Quick actions** — copy PNG straight to the clipboard, save with
  auto-generated filenames, pin, or discard with Escape

## Feedback

Found a bug or have a suggestion? Please
[open an issue](https://github.com/tacshi/aSnap-Release/issues).

When reporting a bug, it helps to include:

- The aSnap version (Settings, or the downloaded file name) and whether it is
  a release or a preview
- Your macOS or Windows version
- Steps to reproduce, and a screenshot or recording if the issue is visual

---

<div align="center">
<sub>© MonkeyT3ch. macOS builds are code-signed and notarized.</sub>
</div>
