# macOS Desktop Customisation

Make your Mac desktop your own.

A macOS customisation app that lets you personalise your desktop with custom docks, floating panels, widgets, layouts, colours, transparency, and themes. Build a workspace that matches your style, workflow, and preferences.

## ✨ Features

- **Custom Docks** — Create and customise docks to organise your apps and shortcuts.
- **Floating Panels** — Add custom panels to your desktop for quick access to useful tools.
- **Widgets** — Design a desktop experience with useful, glanceable information.
- **Custom Layouts** — Arrange and organise interface elements to suit your workflow.
- **Themes and Colours** — Personalise the appearance of your desktop with your own style.
- **Transparency and Blur** — Adjust visual effects to create a cleaner, more polished look.
- **Flexible Positioning** — Customise the placement and arrangement of supported elements.
- **Desktop Profiles** — Set up different configurations for different tasks and preferences.

*Feature availability depends on the current implementation and macOS restrictions.*

## 🎨 Built for Personalisation

Your desktop should work the way you want it to.

Whether you prefer a minimal setup, a productivity-focused workspace, or a heavily customised desktop, this project aims to give you more control over your Mac's appearance and everyday experience.

## 🖥️ Platform

- **Operating System:** macOS
- **Language:** Swift
- **Framework:** SwiftUI, with AppKit where needed
- **Development Environment:** Xcode

## 📥 Installation

### Download a Release

1. Open the [Releases](../../releases) page.
2. Download the latest available macOS release ZIP.
3. Extract the ZIP file.
4. Move the application to your Applications folder.
5. Open the app.

If macOS displays a security warning, verify that the application came from a trusted release. Do not bypass security protections for an untrusted build.

If no releases are available yet, the app has not been published for download.

### Build from Source

1. Clone this repository:

   ```bash
   git clone <YOUR-REPOSITORY-URL>
   ```

2. Open the `.xcodeproj` or `.xcworkspace` file in Xcode, whichever the project provides.
3. Select the macOS app scheme.
4. Choose **My Mac** as the run destination.
5. Build and run the project.

Replace `<YOUR-REPOSITORY-URL>` with the actual URL of this repository.

## ⚙️ macOS Compatibility

This application is designed for macOS. Compatibility depends on the macOS version and the APIs used by the current build.

macOS restricts how third-party applications can modify system interface elements. Some customisations may therefore use independent windows, floating panels, menu bar extras, or other supported APIs rather than replacing protected system components.

## 🤝 Contributing

Suggestions, bug reports, and feature requests are welcome.

If you encounter a problem or have an idea for improving the application, open an issue in this repository with a clear description and steps to reproduce the problem where applicable.

## 🔒 Privacy

Privacy details depend on the features implemented in each release. Check the source code and release notes for information about data collection, network access, and permissions before using a build.

## 📄 License

No license has been specified yet.

Until a license is added to this repository, do not assume that the source code is available for unrestricted reuse, modification, or redistribution.

## 💡 Vision

The goal is simple: give Mac users more freedom to create a desktop that feels like their own.

**Your Mac. Your layout. Your rules.**
released on MacOs 27
