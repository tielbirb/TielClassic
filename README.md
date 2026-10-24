# TielClassic

> An **Android-exclusive** fork of [MojoLauncher](https://github.com/MojoLauncher) built for **Minecraft Infdev through 1.12.2** — with instance management, modloaders, version installation, and Terracotta multiplayer.

[![Platform](https://img.shields.io/badge/platform-Android-3DDC84.svg?logo=android&logoColor=white)]()
[![Minecraft](https://img.shields.io/badge/Minecraft-Infdev%20→%201.12.2-green.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 📖 Overview

TielClassic is an Android app derived from MojoLauncher that focuses entirely on the **classic era of Minecraft: Infdev up to 1.12.2**. It gives you a full mobile launcher experience — install versions, manage instances, load mods, and play multiplayer — without the bloat of modern-version plumbing.

## ✨ Features

- **📱 Android-only** — built as a mobile app, not a desktop launcher
- **🗂️ Instance management** — create, clone, and switch between separate game instances with their own versions, mods, and settings
- **🧩 Modloader support** — install and run Fabric, Forge, and other loaders for supported legacy versions *(adjust to the loaders actually implemented)*
- **⬇️ Version installation** — download and install any supported version (Infdev → 1.12.2) directly in-app
- **🌐 Terracotta multiplayer** — connect to Terracotta-hosted servers for co-op play *(via the Terracotta mod/API)*
- **🎨 Easy UI** — clean, touch-friendly interface designed for phones and tablets
- **⚡ Better than Adventure-style modloader workflow** — streamlined mod loading and instance setup, in the spirit of the Better than Adventure modloader experience
- **Legacy-first** — Infdev through 1.12.2 only; 1.13+ intentionally unsupported

## 📱 Requirements

- **Android version:** *( Android 8.0+ / API 26+)*
- **RAM:** *(4gb)*
- **Storage:** *(500mb)*
- **Java runtime:** handled in-app **
- **Network:** required for version downloads and Terracotta multiplayer

## 🚀 Installation

### From a release (recommended)

1. Download the latest `.apk` from [Releases](https://github.com/tielbirb/TielClassic/releases).
2. Enable "Install from unknown sources" for your file manager/browser.
3. Install and open the app.

### Build from source

```bash
git clone https://github.com/tielbirb/TielClassic.git
cd TielClassic
./gradlew assembleDebuga
