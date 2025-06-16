# TransitAccess

TransitAccess is a prototype application designed to improve the public transit experience for visually impaired individuals. It offers an inclusive, voice-guided interface for managing travel tasks such as buying tickets, planning trips, and requesting boarding assistance — all within a highly accessible environment.

## Purpose

This app is part of a university course project aimed at designing inclusive digital solutions for marginalized populations in the Global North. Our focus is on enabling visually impaired and blind individuals to navigate urban transit systems independently and safely.

## Features

- **Voice-guided account and pass management**
- **TTS-enabled ticket purchase and storage**
- **Real-time bus detection with vibration feedback**
- **Auto check-in/out with exception handling**
- **Journey planning with accessible filters and rerouting**
- **Service alerts and reminders via TTS and haptics**
- **Help center and live support options**
- **Full customization of accessibility settings**

## Tech Stack

- **Frontend**: [Vite](https://vitejs.dev/), TypeScript, React
- **Styling**: Tailwind CSS
- **Accessibility**: Text-to-Speech (TTS), ARIA Live Regions, Voice Commands (planned)
- **Mock Data**: GTFS, GPS simulation, API simulation

## Getting Started

### 1. Clone or Download

```bash
git clone https://github.com/your-username/AccessibleTransport.git
cd AccessibleTransport

**### 2. Install Dependencies**
npm install

**### 3. Start the Development Server**
npm run dev

**### 4. Customize Configuration**
You can modify:
tailwind.config.ts for design tokens
vite.config.ts for build and server settings

📁 Project Structure
AccessibleTransport/
├── components.json
├── tailwind.config.ts
├── vite.config.ts
├── tsconfig.json
├── package.json
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   └── ...
└── ...
♿ Accessibility Design
TTS for all major flows

Voice navigation for command selection

Haptic feedback for critical notifications

Large-text and high-contrast UI themes

Offline support for ticket access

We followed principles from:

Inclusive Design

Design Justice

WAI-ARIA Accessibility

📢 License
This project is for educational project only and not intended for production use.





