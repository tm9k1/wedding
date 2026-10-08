# Nitya & Piyush · wedding invitation

Live at **https://tm9k1.github.io/wedding/**: a scroll-to-open 3D wedding card for 25 November 2026.

## Personal links
The details come in English, हिंदी and తెలుగు (the Telugu is awaiting a proofread by Nitya).

Add `?to=` with the guest's name and it appears on the envelope and in the greeting:

    https://tm9k1.github.io/wedding/?to=Sharma%20Family

(Spaces become `%20`; WhatsApp also accepts the link with plain spaces replaced by `%20`.)

## Settings
Near the top of the `<script>` in `index.html`:
- `RSVP_TO`: a WhatsApp number with country code (e.g. `9198XXXXXXXX`) sends RSVP replies straight to that chat. Empty lets the guest pick the chat.
- `MAP_URL`: the venue's Google Maps pin (set to https://maps.app.goo.gl/aWKCJA8SwJBW33zB7).

## Files
- `index.html`: the page (fonts load from Google Fonts; everything else is inline)
- `og.jpg`: the WhatsApp/social link preview (1200×630)
- `wedding.ics`: the Apple/Outlook calendar entry

GitHub Pages serves the `gh-pages` branch; push `main` to both `main` and `gh-pages`.
