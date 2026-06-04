# MoneySync

A live shared budget app for two users — built as a progressive web app (PWA) you can install on any phone.

## What it does

Two users share a real-time view of a single budget. Each user has their own role:

- **User 1** — adds income and expenses, browses transactions by month, and can action items from User 2's wishlist
- **User 2** — adds items to a wishlist with a target cost, and the app estimates when they can afford each one based on the current balance

Everything syncs instantly between both users with no refresh needed.

## Features

- Real-time sync via Supabase
- Wishlist with affordability calculator — estimates how many paydays away each item is
- Monthly transaction history with income/expense breakdown
- Installable as a PWA on iPhone and Android
- Works offline (service worker caches the app shell)

## Tech stack

- Vanilla HTML/CSS/JS — no build step
- [Supabase](https://supabase.com) for the database and real-time subscriptions
- Deployed on Cloudflare Pages

## Running locally

Just open `index.html` in a browser — no install needed. The app connects to a hosted Supabase project so data loads automatically.
