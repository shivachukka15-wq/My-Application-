# MovieHub - JavaScript Movie Booking App

A beginner-friendly movie ticket booking application inspired by the basic booking flow of apps such as BookMyShow.

## Features

- Movie selection
- 30-seat layout
- Seat selection/deselection
- Automatic price calculation
- Booking validation
- Booking success message
- Booking window automatically closes after successful booking

## How to run

1. Extract the ZIP file.
2. Open `index.html` in a browser.
3. Click **Book Now**.
4. Select a movie and seats.
5. Click **Confirm Booking**.
6. The success message appears and the booking window closes automatically.

## Important browser note

`window.close()` is normally permitted when the current page was opened by JavaScript using `window.open()`. That is why this project opens `booking.html` from `index.html`.

This is a front-end demo. It does not connect to a real database or payment gateway.
