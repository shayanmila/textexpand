# Masoom Text Expander
Independent, no-subscription Chrome Manifest V3 extension for locally stored snippets and typing shortcuts.

## Install
Download the ZIP from [Releases](https://github.com/shayanmila/textexpand/releases), extract it, then open `chrome://extensions`, enable **Developer mode**, click **Load unpacked**, and select the extracted folder containing `manifest.json`.

## Features
- Create, edit, delete and search text snippets, organized by folder.
- Expand a shortcut such as `/thanks` in standard editable fields on websites.
- Dynamic placeholders: `{date}`, `{time}`, `{datetime}`, `{url}`, `{domain}`.
- Right-click insertion menu.
- JSON import/export backup.
- All snippet data stays in the browser's local extension storage; no login or API.

## Known limitations
Some rich text editors, browser internal pages, password fields, and native desktop applications are not supported. This is an original independent implementation, **not** a feature-complete replica of Text Blaze.

## Release workflow
Use **Actions → Release Chrome Extension → Run workflow** to create a release ZIP. The workflow is manual/release-based (no build on every push). Tag `v1.0.1` may also trigger it.

## Privacy
No analytics, remote API, or cloud sync. The content script only checks typed text in editable fields to recognize shortcuts.
