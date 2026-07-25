# Quicher

A QR code and barcode toolchest that runs entirely in the browser. No ads, no tracking, no paywalls, no uploads. Installable as a PWA so it works on desktop and phone, online or off.

Live at [qr.puncraft.ca](https://qr.puncraft.ca).

## Why the name

It has nothing to do with QR codes, beyond containing a Q and an R.

A few days before this project started, I asked my Google speaker "what can I do with a lot of eggs I have". It suggested breakfasts, frittatas, and quiches - except it mispronounced the last one as "kwitch-es". I howled. The name stuck.

## Features

- Generate QR codes for URLs, plain text, WiFi credentials, vCards, email, SMS, and phone numbers
- Generate barcodes
- Scan QR codes and barcodes with the camera
- Download as PNG or SVG
- Five colour themes
- Hash-based deep links, so `#wifi` opens straight to the WiFi form (also `#url`, `#text`, `#vcard`, `#email`, `#sms`, `#phone`, and the `#qr` / `#bc` / `#scan` tabs)

## Running it

It is a static site. Open `index.html`, or serve the directory with any static file server.

Deployed via GitHub Pages, with the custom domain set in `CNAME`.
