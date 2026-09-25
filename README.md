# Finer

**Finer** is a lightweight personal financial health tracker designed to help users record day-to-day income and expenses, understand spending patterns, and monitor their overall financial health.

## Features

- Personal sign-in screen with email and simulated Google sign-in
- Dashboard with income, expenses, net balance, and transaction count
- Add and categorise income and expenses
- Transaction history with income/expense filters
- Spending analysis with charts
- Financial health score based on:
  - Savings rate
  - Spending control
  - Income stability
  - Expense diversity
- Personalised financial tips
- Multiple currency options
- Light and dark mode
- Responsive layout for desktop and mobile
- Local data storage using the browser's `localStorage`

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Chart.js
- Tabler Icons
- Browser `localStorage`

## Project Structure

```text
Finer/
├── index.html
├── README.md
├── assets/
└── screenshots/
```

## Getting Started

No build tools are required.

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Sign in and start adding transactions.

For GitHub Pages, enable **Pages** in the repository settings and deploy from the `main` branch.

## Data & Privacy

Finer currently stores user profiles, preferences, and transactions locally in the browser using `localStorage`. No backend database is included in this version.

The current **Continue with Google** interface is a simulated sign-in flow for the front-end prototype; it does not implement Google's OAuth authentication.

## External Dependencies

The application loads Chart.js and Tabler Icons from public CDNs. An internet connection is therefore required for those external resources to load.

## Current Scope

This repository represents a front-end prototype of Finer. It is intended for personal finance tracking and demonstration purposes rather than regulated financial advice or production financial services.

## Roadmap

Potential future improvements:

- Real Google OAuth authentication
- Secure backend/database
- Cloud synchronisation across devices
- Export transactions to CSV
- Budget goals and alerts
- Recurring transactions
- More detailed financial reports
- Automated backups
- Improved accessibility and testing

## License

No license is included at this stage.
