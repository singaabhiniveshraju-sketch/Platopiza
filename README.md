# FlashBite — Hyper-Fast 20-Minute Food Delivery App

A React + Tailwind CSS food delivery web application featuring a **20-Minute Delivery Guarantee (or ₹100 Instant Cashback)**, **FlashPass VIP Membership**, **7-Day Foodie Streaks**, **Daily Craving Spin Wheel**, and optional **Google Drive Cloud Database (`flashbite_db.json`)**.

## Quick Start

```bash
npm install
npm run dev
```

## Optional: Enable Google Drive as Your Database
1. Create an OAuth 2.0 Web Client ID in [Google Cloud Console](https://console.cloud.google.com/) with **Google Drive API** enabled and `http://localhost:5173` added to Authorized JavaScript origins.
2. Create a `.env` file in the project root:
   ```env
   VITE_GOOGLE_CLIENT_ID=your-client-id.apps.googleusercontent.com
   ```
3. Click **Sync Drive DB** in the top header to create and auto-sync `flashbite_db.json` in your Google Drive.
