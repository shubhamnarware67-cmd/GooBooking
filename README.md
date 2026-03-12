<div align="center">

<img src="https://img.shields.io/badge/GooBooking-🎬%20Ticket%20Booking%20Platform-e8001d?style=for-the-badge&labelColor=0a0a0f" alt="GooBooking" />

# 🎟️ GooBooking

### India's Real-World Movie & Event Ticket Booking Web App

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-Visit%20Now-06d6a0?style=for-the-badge)](https://shubhamnarware67-cmd.github.io/GooBooking)
[![GitHub Repo](https://img.shields.io/badge/GitHub-shubhamnarware67--cmd-181717?style=for-the-badge&logo=github)](https://github.com/shubhamnarware67-cmd/GooBooking)
[![License](https://img.shields.io/badge/License-MIT-ffd166?style=for-the-badge)](LICENSE)
[![Made by Shubham](https://img.shields.io/badge/Made%20by-Shubham%20Narware-e8001d?style=for-the-badge)](https://github.com/shubhamnarware67-cmd)

<br/>

> A fully functional, real-world **BookMyShow-inspired** ticket booking platform built with **HTML, CSS & Vanilla JavaScript** — featuring movie listings, interactive seat selection, and a complete payment flow.

<br/>

![GooBooking Banner](https://via.placeholder.com/900x350/0a0a0f/e8001d?text=🎬+GooBooking+–+Book+Movies%2C+Events+%26+More)

</div>

---

## 📌 Table of Contents

- [✨ Features](#-features)
- [🎬 Live Preview](#-live-preview)
- [🖼️ Screenshots](#️-screenshots)
- [🛠️ Tech Stack](#️-tech-stack)
- [📁 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
- [🎯 How It Works](#-how-it-works)
- [📦 Data & Content](#-data--content)
- [🔮 Future Scope](#-future-scope)
- [👨‍💻 Author](#-author)
- [📄 License & Copyright](#-license--copyright)

---

## ✨ Features

### 🎬 Movies
- **Now Showing** — 12+ live movies with ratings, genres, duration & certificate
- **Premieres & Exclusives** — Featured banner cards
- **Upcoming Releases** — Reverse-listed upcoming content
- **Real-time Search** — Filter movies by name or genre instantly

### 🗓️ Booking Flow
- **Date Selector** — Choose from next 8 days including Today & Tomorrow
- **Cinema & Showtime Picker** — Multiple cinemas (PVR, INOX, Cinepolis) with various show slots
- **Interactive Seat Map** — 8 rows × 12 seats with Premium (Gold), Available, Selected & Booked states
- **Smart Seat Validation** — Max 6 seats per booking, real-time price calculation
- **Booking Summary** — Live ticket count, seat IDs, show details & total fare

### 💳 Payment System
- **UPI / QR Code** — PhonePe, GPay, Paytm
- **Credit / Debit Card** — With card number, expiry & CVV fields
- **Net Banking** — All major banks
- **Wallets** — Paytm, Amazon Pay
- **Booking Confirmation** — Unique Booking ID (e.g. `GOO3F8K2A`) with receipt

### 🎵 Events, Sports & More
- Live Events (Arijit Singh Live, Sunburn Festival, EDM Night)
- Sports (IPL 2026, Pro Kabaddi, ISL Football, WWE)
- Plays & Theatre (Prithvi, NCPA)
- Fun Activities (Escape Room, Bungee Jumping, Workshops)

### 🌟 UI/UX
- Auto-rotating Hero Banner (4 slides, 4.5s interval)
- Category Tabs with smooth scroll
- Toast Notifications
- City Selector (8 major Indian cities)
- Sign In / Register Modal with Google OAuth button
- Fully Responsive Design (Mobile & Desktop)
- Dark theme with premium aesthetics

---

## 🎬 Live Preview

<div align="center">

### 👉 [https://shubhamnarware67-cmd.github.io/GooBooking](https://shubhamnarware67-cmd.github.io/GooBooking)

> Open the link above to experience the full booking flow live in your browser!

</div>

---

## 🖼️ Screenshots

| Home Page | Movie Detail Modal |
|-----------|-------------------|
| 🎬 Hero banner with movies & events | 🪑 Seat picker & showtime selector |

| Payment Screen | Booking Confirmation |
|----------------|---------------------|
| 💳 Multiple payment methods | 🎉 Unique booking ID & receipt |

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5** | Structure & semantic layout |
| **CSS3** | Animations, gradients, responsive grid |
| **Vanilla JavaScript (ES6+)** | Dynamic UI, state management, booking logic |
| **Google Fonts** | Syne (headings) + DM Sans (body) |
| **CSS Variables** | Consistent theming & dark mode |
| **CSS Grid & Flexbox** | Responsive layouts |

> ⚡ **Zero dependencies** — No React, No Vue, No frameworks. Pure HTML/CSS/JS!

---

## 📁 Project Structure

```
GooBooking/
│
├── index.html          # Main application (single-file architecture)
├── README.md           # Project documentation
├── LICENSE             # MIT License
│
└── assets/             # (optional)
    ├── screenshots/    # App screenshots
    └── favicon.ico     # Site favicon
```

> The entire application lives in a **single `index.html` file** — no build tools, no npm install required.

---

## 🚀 Getting Started

### Option 1: Direct Open (Easiest)
```bash
# Just open the HTML file in any browser
# No server required!
open index.html
```

### Option 2: Clone & Run
```bash
# 1. Clone the repository
git clone https://github.com/shubhamnarware67-cmd/GooBooking.git

# 2. Navigate into the project
cd GooBooking

# 3. Open in browser
start index.html       # Windows
open index.html        # macOS
xdg-open index.html    # Linux
```

### Option 3: VS Code Live Server
```bash
# Install Live Server extension in VS Code
# Right-click index.html → "Open with Live Server"
```

### Option 4: GitHub Pages
The live version is deployed at:
```
https://shubhamnarware67-cmd.github.io/GooBooking
```

---

## 🎯 How It Works

```
User Opens Site
      │
      ▼
 Hero Banner ──► Auto-rotates every 4.5s
      │
      ▼
 Browse Movies / Events / Sports / Plays / Activities
      │
      ▼
 Click a Movie Card
      │
      ▼
 Movie Modal Opens
      ├── Select Date (8 days)
      ├── Select Cinema & Showtime
      └── Interactive Seat Map (8 × 12 grid)
            │
            ▼
         Booking Summary (live price)
            │
            ▼
         "Proceed to Pay"
            │
            ▼
         Payment Modal
         ├── UPI / Card / Netbanking / Wallet
         └── Pay Securely
               │
               ▼
            ✅ Booking Confirmed!
            (Unique ID like GOO3F8K2A)
```

---

## 📦 Data & Content

### Movies (12 titles)
Kalki 2898 AD • Pushpa 2 • Devara • Singham Returns • Fighter • Oppenheimer • Dune Part Two • Animal • Stree 2 • Lucky Baskhar • Merry Christmas • Sky Force

### Events (6)
Arijit Singh Live • EDM Revolution • Comedy Night with Zakir • Sunburn Festival • Stand-Up Comedy Slam • Indie Music Night

### Sports (4)
IPL 2026 MI vs CSK • Pro Kabaddi League • ISL Mumbai City FC • WWE SmackDown India Tour

### Cinemas (5)
PVR Juhu • INOX Atria Mall • Cinepolis Versova • PVR Phoenix Marketcity • BookMyShow Stream

---

## 🔮 Future Scope

- [ ] Backend integration (Node.js + MongoDB)
- [ ] Real TMDB API for live movie data
- [ ] User authentication (JWT)
- [ ] Razorpay / Stripe real payment gateway
- [ ] Email confirmation using NodeMailer
- [ ] QR Code ticket generation
- [ ] Admin dashboard for show management
- [ ] PWA (Progressive Web App) support
- [ ] Multi-language support (Hindi, Marathi, Tamil)
- [ ] React.js migration for scalability

---

## 👨‍💻 Author

<div align="center">

### **Shubham Narware**

🎓 3rd Year Computer Science Student  
💻 Passionate Full-Stack Developer  
🌏 India

[![GitHub](https://img.shields.io/badge/GitHub-shubhamnarware67--cmd-181717?style=for-the-badge&logo=github)](https://github.com/shubhamnarware67-cmd)

> *"Building real-world projects to learn real-world skills."*

</div>

---

## 📄 License & Copyright

```
MIT License

Copyright (c) 2026 Shubham Narware

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

> ⚠️ **Disclaimer:** GooBooking is a **student project** built for educational purposes only.  
> It is **not affiliated with** BookMyShow, PVR, INOX, or any real ticketing platform.  
> All movie names, event names, and brand references are used for demonstration only.

---

<div align="center">

**Made with ❤️ by [Shubham Narware](https://github.com/shubhamnarware67-cmd)**

⭐ **If you found this useful, please star the repo!** ⭐

[![Star on GitHub](https://img.shields.io/github/stars/shubhamnarware67-cmd/GooBooking?style=social)](https://github.com/shubhamnarware67-cmd/GooBooking/stargazers)

</div>
