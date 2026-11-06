# PayMoji travel cost calculator

**Live:** https://paymoji-trip-cost.netlify.app

A free calculator for travellers planning Vietnam, the Philippines or Bali. Pick a country, the number of days and a travel style, and it shows the daily cost of food, rides and stays in your home currency, plus what your bank takes in card and ATM fees.

![Travel cost calculator](screenshot.png)

## Pages

- `/` Southeast Asia overview and comparison
- `/vietnam/`, `/philippines/`, `/bali/` budget per day, how much money to bring, ATM fees and how to pay as a tourist

## How it works

Static HTML with no framework and no backend. Exchange rates come from [open.er-api.com](https://open.er-api.com). Prices and fees live in the `COUNTRIES` and `PAYMOJI` settings in the script, and the tables on each page are built from the same numbers.

## Run it locally

```
python3 -m http.server 8000
```

Made for [PayMoji](https://www.paymoji.app/), the travel wallet for Southeast Asia.
