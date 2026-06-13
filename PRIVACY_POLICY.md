# Privacy Policy — Tab Memory Manager

_Last updated: 2026-06-13_

Tab Memory Manager is built to be private by design. This policy explains what the
extension does and does not do with your information.

## The short version

**Tab Memory Manager does not collect, transmit, sell, or share any of your data.**
Everything the extension does happens locally, inside your own browser. There are no
servers, no accounts, no analytics, and no tracking.

## What the extension accesses

To do its job, the extension reads information about your **currently open tabs** —
their titles, URLs, favicons, audio/pinned/discarded state, and last-active times.
It also reads your device's total and available system memory. This information is
used only to:

- estimate and display how much memory each tab and Chrome are using;
- group tabs by website;
- detect duplicate tabs;
- suggest idle tabs you may want to hibernate or close;
- show site icons in the list.

## What is stored, and where

The extension saves the following **locally on your device only**, using Chrome's
`storage` API:

- your settings (e.g. cleanup thresholds, whitelisted domains, options);
- short-lived per-tab activity timestamps;
- a short "Recently cleaned" list so you can undo a cleanup;
- aggregate lifetime stats (tabs cleaned, estimated memory freed).

This data never leaves your browser. It is not sent anywhere, and it is not
accessible to us or any third party.

## What is NOT collected

- No personal information.
- No browsing history beyond the tabs currently open in your browser.
- No data is sent to any external server.
- No advertising or analytics identifiers.

## Optional permissions

- **Floating widget (host access):** if you enable the on-page memory widget, the
  extension is granted access to display a small overlay on pages. It does not read
  or transmit page content.
- **Exact memory (`processes`, Chrome Dev/Canary only):** if you enable this, the
  extension reads real per-tab memory from Chrome's local process API. This data is
  used only for on-screen display and never leaves your device.

Both are off by default and requested only when you turn them on.

## Changes to this policy

If this policy changes, the "Last updated" date above will be revised.

## Contact

Questions about privacy? Contact: rkmohanchn@gmail.com
