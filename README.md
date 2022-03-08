# Fastmail Plus (Chrome Extension)

![](https://github.com/yohasebe/fastmail-plus/blob/main/images/fastmail-plus-128.png?raw=true)

A Chrome extension to make **Fastmail** (https://fastmail.com) web UI more usable and productive

## Functionality

- [Badge notification for unread messages to Inbox](#badge-notification-for-unread-messages-to-inbox)
- [Faster switch between different search modes](#faster-switch-between-search-modes) (anywhere/subject and body/subject only)
- [Easier button operation in conversation view](#easier-button-operation-in-conversation-view)
- [Change focus using `↑` and `↓` cursor keys](#change-focus-using-updown-cursor-keys)
- [Extra shortcut keys](#extra-shortcut-keys)
- [Fix problem with IME in default search input](#fix-problem-with-ime-in-search-input-box)
- [Others](#others)

## Installation

### Chrome Web Store

In preparation

### Manual Installation

1. Clone this repository or download Zip
2. Visit `chrome://extensions/` and turn on "Developer mode"
3. Click "Load unpacked" button and specify the folder downloaded from GitHub

## Description/Usage

### Badge notification for unread messages to Inbox

The number of unread messages to Inbox appears in icon badge and is updated when Chrome has a tab for Fastmail.

<img width="36" alt="badge" src="https://user-images.githubusercontent.com/18207/157005260-ab05b20f-1751-42c5-ad63-afa4d5727db9.png">

### Faster Switch between Search Modes

Pressing the "repeat arrow" button cyclically switches three different search modes:

- Search anywhere (default)
- Search in subject and body
- Search in subject only

<br />

![fastmail-plus-alt-search](https://user-images.githubusercontent.com/18207/156918109-aeef285c-1f15-4bd6-9cfe-c22a2b954a36.gif)

### Easier Button Operation in Conversation View

Requirement: `Group messages with their replies` is enabled in Fastmail Settings

An set of extra control buttons are presented on the right-bottom corner of the window. The following will be included (from left to right)

- Toggle uncluttered-view mode (only when "Hide reading pane" is selected)
- Focus previous message in conversation
- Focus next message in conversation
- Toggle currently focused message
- Ungroup/Expand messages
- Collapse messages
- Toggle show/hide extra control

<br />

![conversation-control](https://user-images.githubusercontent.com/18207/156918099-274bb6ea-aa2f-4202-9ce9-7923e3ca0c61.gif)

### Change Focus Using Up/Down Cursor Keys

When `Show reading pane` is selected in Fastmail Settings:

`↑` and `↓` cursor keys can be used (in addition to `P` and `N` )to move focus in conversation panel in the right-hand side of the window.

When `Hide reading pane` is selected in Fastmail Settings:

`↑` and `↓` cursor keys can be used (in addition to `J` and `K` )to move focus in messages panel.

`↑` and `↓` cursor keys can be used (in addition to `P` and `N` )to move focus in conversation panel.

### Extra Shortcut Keys

If enabled, extra shortcut keys view will be added

- Switch between search modes: `Control + S`
- Toggle uncluttered-view mode (when "Hide reading pane" is selected): `Control + L`
- Toggle show/hide extra control: `Control + ,`
- Toggle currently focused message: `Enter` (in addition to the default `E`)
- Ungroup/Expand messages: `Shift + Enter` (in addition to the default `Shift + E`)
- Collapse messages: `Shift + Option/Alt + Enter` (in addition to the default `Shift + Option/Alt + E`)
- Show/hide right-hand side panel: `Shift + Control + I` (in addition to the default `Shift + Command + I`)
- Prev in Calendar view: `Control + ↑` (in addition to `K`)
- Next in Calendar view: `Control + ↓` (in addition to `J`)

### Fix Problem with IME in Search Input Box

When entering Japanese (or some other language) in Fastmail's search input, using the IME to enter text requires pressing the Enter key before completing the input. Fastmail's Web UI performs the search at the moment the Enter key is hit even though the search string is completed. Fastmail Plus fixes this problem.

### Others

- Visually show if the focused message is made in plain text (a gray vertical bar appears on the left border of the message) or not
- Fold the "reply-to" part of a message (`appendonsend`)

## Advertisement

Sign up for Fastmail through this link and get **10% off** for one year.

https://ref.fm/u27773408

## Author

Yoichiro Hasebe

## License

The MIT License

## Disclaimer

Fastmail Plus Chrome Extension is not officially endorsed by Fastmail. Use this open source software at your own risk and do not contact Fastmail for support.
