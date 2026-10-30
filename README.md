# BizBoard — Releases

This public repository hosts **BizBoard installer downloads** (Windows) and the
`latest.yml` feed the app's built-in auto-updater reads.

BizBoard is a personal desktop app for running every business, every day:
add your businesses, give each one its daily tasks on a Kanban board, and
see at a glance which business still needs attention today.

## Install

1. Download the latest `BizBoard Setup x.y.z.exe` from
   [Releases](https://github.com/thisnaeem/bizboard-releases/releases).
2. Double-click it (per-user install, no admin needed). Windows SmartScreen
   may warn once because the installer is unsigned — choose
   "More info" → "Run anyway".
3. After that, BizBoard updates itself: new versions download in the
   background and install when you click "Restart & update" in the app.

The app is fully offline for your data — businesses, tasks and logos live
in one JSON file on your own PC (`%APPDATA%\BizBoard\bizboard-data.json`).
Only the update check talks to this repository.
