# Expense Tracker — React + Vite

## Run in VS Code

1. Extract the ZIP and open the `ExpenseTracker-review-copy` project folder in VS Code.
2. Select **Terminal → New Terminal**.
3. Run `npm install` once.
4. Run `npm run dev` and open the localhost URL printed by Vite (usually `http://localhost:5173`).

To create a production build, run `npm run build`; Vite writes it to `dist/`.

## Project modules

- **User:** signup/login, income and expense tracking, budgets, accounts, recurring expenses, reports, and CSV export.
- **Admin:** registered account list and account counts. Users' financial records are not displayed in the Admin module.

Demo admin login: `admin@gmail.com` / `admin123`.

## Vercel

The included `vercel.json` supports the Vite single-page app. Import the GitHub repository into Vercel and deploy with the Vite defaults (`npm run build`, output folder `dist`).

## Demo limitation

This is a frontend-only academic project. Signup, passwords, and financial records are stored in Local Storage in the current browser profile. There is no server-side authentication or shared database. Do not use real financial data or treat this prototype as a secure production service.
"# FRONTENDPROJECT1" 
