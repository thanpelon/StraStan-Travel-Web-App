This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

Welcome to **My Next.js Project**! This application features a robust flight booking system with a variety of useful functionalities.

This project uses a mix of React, TailwindCSS, and Shadcn elements for the UI.

## Features

- **Flights Search**: A comprehensive search bar that allows users to search by trip type, cabin class, passenger type, origin, destination (with live search), departure and return date. Includes an option to view direct flights only.
- **Global Currency Selector**: Easily switch between different currencies.
- **Flight Results Filtering**: Filter results by airlines, number of stops, time, duration, and price per person.
- **Detailed Flight Information**: View detailed information for each flight, including aircraft type, baggage allowance, cabin class, and pricing details.
- **Flight Segments**: Display information about flight segments, including departure and arrival times, duration, and layover details.
- **Flight Order Page**: Dynamically generated fields based on passenger type and number, including flight details and a total counter for proceeding to payment.

## Flight Section Details

At the start screen, you will find a comprehensive search bar for flights, which includes:
- Trip Type
- Cabin Class
- Passenger Type
- Origin and Destination (both with live search)
- Departure and Return Date
- Option to see direct flights only

### Flight Results

The search results can be filtered by:
- Airlines
- Number of Stops
- Time
- Duration
- Price per Person

Sample flight details are displayed as follows:
- **Aircraft**: [Aircraft Type]
- **Baggage Allowance**: [Baggage Details]
- **Cabin Class**: [Cabin Class]
- **Traveler Price**: [Price] [Currency]
- **Fare Type**: [Fare Type]
- **Branded Fare**: [Branded Fare]
- **Base Price**: [Base Price] [Currency]
- **Total Price**: [Total Price] [Currency]
- **Grand Total**: [Grand Total] [Currency]

**Pricing per Traveler:**
- ADULT: [Price] [Currency]

**Amenities:**
- [List of amenities]

### Flight Segments

Example of flight segments:
- **Departure Airport** (Code) to **Arrival Airport** (Code)
  - **Carrier**: [Carrier]
  - **Flight Number**: [Flight Number]
  - **Departure**: [Date and Time]
  - **Arrival**: [Date and Time]
  - **Duration**: [Duration]
  - **Aircraft**: [Aircraft Type]
  - **Operated by**: [Carrier]
  - **Layover**: [Location], Duration: [Layover Duration]

## Get Flight Order Page

The Flight Order Page dynamically updates based on the number and type of passengers. It includes:
- Flight details
- Total counter for proceeding to payment

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
