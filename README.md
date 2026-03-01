# 🔲 Nextqr

> A powerful single-file QR code generator supporting **25 QR types** — URLs, contacts, Wi-Fi, payments, events & more. No frameworks. No backend. No data stored. Just open and use.

![Version](https://img.shields.io/badge/version-1.0.0-355872?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-7AAACE?style=flat-square)
![HTML](https://img.shields.io/badge/built%20with-HTML%20%2F%20CSS%20%2F%20JS-9CD5FF?style=flat-square)
![Offline](https://img.shields.io/badge/works-offline-355872?style=flat-square)
![No Backend](https://img.shields.io/badge/backend-none-7AAACE?style=flat-square)

---

## 📸 Preview

> Clean, minimal UI with a calm blue palette (`#355872`, `#7AAACE`, `#9CD5FF`, `#F7F8F0`) designed for readability and professional use across all screen sizes.

---

## ✨ Features at a Glance

- ✅ **25 QR code types** organized into 6 smart categories
- ✅ **Single HTML file** — no installation, no server, no dependencies
- ✅ **Works fully offline** after the first load
- ✅ **Mobile-first** responsive design
- ✅ **Download as PNG** with one tap
- ✅ **Copy encoded data** to clipboard instantly
- ✅ **Smart dropdown UI** with grouped categories and icons
- ✅ **Zero data collection** — everything stays on your device
- ✅ **Free forever** — open source under MIT license

---

## 🗂️ QR Code Types (All 25)

### 🌐 Web & Communication
| # | Type | Description |
|---|------|-------------|
| 1 | **URL / Link** | Encode any website URL with auto `https://` detection |
| 3 | **Plain Text** | Encode any raw text message or note |
| 5 | **Email Composer** | Pre-fill recipient, subject, and body of an email |
| 6 | **SMS Message** | Send a pre-written text to any phone number |
| 7 | **Phone Call** | Dial a number instantly on scan |
| 8 | **WhatsApp Chat** | Open a WhatsApp conversation with a pre-filled message |

### 👤 Identity & Contact
| # | Type | Description |
|---|------|-------------|
| 2 | **Contact Card (vCard)** | Share full contact details in standard vCard format |
| 25 | **Digital Business Card** | Name, title, company, phone, email, address & website |
| 16 | **Resume / Portfolio** | Link directly to your portfolio, CV, or personal site |
| 10 | **Social Media Profile** | Share Instagram, LinkedIn, Twitter, TikTok & more |

### 💰 Payments & Finance
| # | Type | Description |
|---|------|-------------|
| 9 | **Digital Payment** | UPI, PayPal, Venmo, or any payment link with amount & note |
| 22 | **Cryptocurrency Wallet** | BTC, ETH, LTC wallet address with optional amount |
| 24 | **Coupon / Discount Code** | Encode discount codes, expiry dates, and brand info |

### 📍 Location & Events
| # | Type | Description |
|---|------|-------------|
| 12 | **Google Maps Location** | Address or geo-coordinates for instant navigation |
| 13 | **Calendar Event** | iCal-compatible event with title, time, location & notes |
| 15 | **Event Ticket / Entry Pass** | Event name, ticket ID, seat, gate, and date |

### 📱 Apps & Media
| # | Type | Description |
|---|------|-------------|
| 11 | **App Store / Play Store** | Link users directly to your app on iOS or Android |
| 18 | **YouTube / Video Link** | Direct link to any video with optional title |
| 19 | **Spotify / Music Playlist** | Share playlists, albums, or tracks |
| 20 | **Document / PDF Link** | Google Drive, Dropbox, or any document URL |

### 🔧 Utilities & Tools
| # | Type | Description |
|---|------|-------------|
| 4 | **Wi-Fi Password** | WPA/WPA2, WEP, or open network — connect without typing |
| 14 | **Digital Menu** | Restaurant menu URL with optional name |
| 17 | **Product Information** | Product name, URL, and SKU/barcode |
| 21 | **2FA Setup (Authenticator)** | TOTP secret key for Google Authenticator & compatible apps |
| 23 | **Feedback / Survey Form** | Google Forms, Typeform, or any survey link |

---

## 🚀 Getting Started

### Option 1 — Use Directly (Recommended)
No installation needed. Just download and open.

```bash
# Clone the repository
git clone https://github.com/sonuishere/nextqr.git

# Navigate into the folder
cd qr-code-generator

# Open in your browser
open index.html
```

### Option 2 — Download the File
1. Go to the repository
2. Click `index.html`
3. Click **Download Raw**
4. Open the file in any browser — Chrome, Safari, Firefox, Edge

### Option 3 — Use on Mobile
1. Download `index.html` to your phone
2. Open with Chrome or Safari
3. Use it fully offline — no internet required after first load

---

## 🛠️ How to Use

1. **Open** `index.html` in any browser
2. **Select** a QR type from the smart dropdown menu
3. **Fill in** the required fields for your chosen type
4. **Tap** the **Generate QR Code** button
5. **Download** the QR as a PNG or **Copy** the encoded data
6. **Share** or print your QR code anywhere

---

## 🌍 Real-World Use Cases

| Industry | How to Use |
|----------|------------|
| 🏢 **Business** | Business cards, company profiles, payment links |
| 🍽️ **Restaurants** | Contactless menus, table ordering, feedback forms |
| 🎓 **Education** | Homework links, tutorial videos, resource sheets |
| 🏥 **Healthcare** | Patient info, appointment booking, prescription links |
| 🎟️ **Events** | Digital tickets, venue maps, speaker schedules |
| 🛍️ **Retail** | Product pages, discount codes, loyalty programs |
| 🏠 **Real Estate** | Property listings, virtual tours, agent contact |
| ✈️ **Travel** | Boarding passes, hotel check-in, attraction guides |
| 🔐 **Security** | 2FA setup, secure credential sharing |
| 💼 **Freelancers** | Portfolio links, client onboarding, invoice payment |

---

## 🧱 Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure & layout |
| **CSS3** | Styling, animations, responsive design |
| **Vanilla JavaScript** | Logic, QR generation, clipboard, download |
| **[QRious v4.0.2](https://github.com/neocotic/qrious)** | QR code rendering on HTML5 Canvas |

> No React. No Vue. No Node. No build tools. Just one file.

---

## 📁 Project Structure

```
qr-code-generator/
│
├── index.html          # The entire application — HTML + CSS + JS in one file
├── README.md           # This documentation file
└── LICENSE             # MIT License
```

---

## 🎨 Color Palette

The UI uses a carefully selected calm blue palette for maximum readability and professionalism.

| Role | Color | Hex |
|------|-------|-----|
| Primary / Dark | Dark Steel Blue | `#355872` |
| Secondary | Medium Blue | `#7AAACE` |
| Accent / Border | Sky Blue | `#9CD5FF` |
| Background | Off-White | `#F7F8F0` |

---

## 📦 QR Data Formats Used

| Type | Format Standard |
|------|----------------|
| Contact / Business Card | `vCard 3.0` |
| Wi-Fi | `WIFI:T:WPA;S:SSID;P:pass;;` |
| Email | `mailto:` URI |
| SMS | `sms:` URI |
| Phone Call | `tel:` URI |
| WhatsApp | `https://wa.me/` |
| Calendar Event | `iCalendar (VCALENDAR)` |
| Location | `geo:` URI / Google Maps URL |
| 2FA Auth | `otpauth://totp/` |
| Crypto | `bitcoin:` / `ethereum:` URI |
| All others | Plain URL or structured text |

---

## 🔒 Privacy & Security

- **No server** — all QR generation happens locally in your browser
- **No analytics** — zero tracking, no cookies, no logs
- **No data sent** — your inputs never leave your device
- **No login required** — open and use instantly
- **Safe for sensitive data** — Wi-Fi passwords, crypto wallets, 2FA keys stay private

---

## 🤝 Contributing

Contributions, bug reports, and feature requests are welcome!

```bash
# Fork the repository
# Create your feature branch
git checkout -b feature/new-qr-type

# Commit your changes
git commit -m "Add: New QR type for XYZ"

# Push to your branch
git push origin feature/new-qr-type

# Open a Pull Request
```

Please follow the existing code style and keep all changes within the single-file architecture.

---

## 🗺️ Roadmap

- [ ] QR code color customization (foreground & background)
- [ ] Logo/image overlay on QR center
- [ ] Export as SVG
- [ ] QR code history (local storage)
- [ ] Dark mode toggle
- [ ] Batch QR generation
- [ ] QR code scanner / reader
- [ ] PWA support (installable on mobile)

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute for personal and commercial projects.

See [LICENSE](./LICENSE) for full details.

---

## 🙏 Acknowledgements

- [QRious](https://github.com/neocotic/qrious) — lightweight QR code generation library
- Color palette inspired by calm, professional UI design principles
- Built with ❤️ for developers, designers, and everyday users

---

## 📬 Contact & Support

If you found this project helpful, consider giving it a ⭐ on GitHub — it helps others discover it!

For bugs or feature requests, open an [Issue](https://github.com/sonuishere/nextqr/issues).

---

<div align="center">
  <strong>Made with ❤️ · Open Source · Free Forever</strong><br/>
  <sub>Nextqr © 2025 — MIT License</sub>
</div>
