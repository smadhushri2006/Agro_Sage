# AgroSage Local Demo

This is a lightweight frontend-only demo extracted/reworked from the uploaded AgroSage project so it can run locally without Docker, PostgreSQL, Python, or XGBoost.

## Run

```powershell
npm install
npm run dev
```

Open the localhost URL printed by Vite (normally http://localhost:5173).

## Demo login

Farmer: 9888888888 / Demo@1234
Admin: 9999999999 / Demo@1234

The demo stores login state and prediction history in browser localStorage. Price forecasts are illustrative demo estimates, not live market data.
