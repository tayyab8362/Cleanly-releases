# Privacy Policy — Cleanly

**Short version: Cleanly has no accounts, no analytics and no tracking.**

Cleanly makes exactly two kinds of network requests, both under your control:

1. **Licence activation** — when you paste your licence key, it is sent once to Gumroad's
   licence-verification API to confirm the purchase. Only the key is sent. The result is
   stored on your Mac as a yes/no flag; nothing else is kept or transmitted.
2. **Update check** — about once a day Cleanly downloads a small text file (the "appcast")
   from GitHub to see whether a newer version exists. This request contains no personal
   data. You can turn it off in *Settings → Updates*.

Everything else:

- **No data collection.** No analytics, crash reports, telemetry, identifiers or accounts.
- **No key logging.** During a cleaning session Cleanly discards keyboard and trackpad
  events so they don't reach other apps. It does not read, store or transmit them — the
  code that drops a key never inspects which key it was. The lock exists only while a
  session is running.
- **Accessibility permission** is optional and used solely to pause input system-wide
  while you clean.
- **Stored locally:** your settings, the licence key and its verified flag, in the standard
  macOS preferences file for this app.

Questions: open an issue at https://github.com/tayyab8362/Cleanly-releases/issues
