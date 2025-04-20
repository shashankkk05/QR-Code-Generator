# QR Code Generator 🧩

This is a simple and clean **QR Code Generator** web application built using **HTML**, **CSS**, and **JavaScript**.  
It allows users to easily generate QR codes for any text or URL!

---

## Features ✨

- Generate QR codes instantly for any text or link
- Simple and clean user interface
- QR Code displays dynamically on button click
- Error handling for empty input
- Mobile-friendly (with a little CSS tweaking)

---

## Demo 📸

> Enter any text or URL → Click **Generate QR Code** → Your QR Code will appear below!

---

## Technologies Used 💻

- HTML5
- CSS3
- JavaScript (Vanilla)
- [QR Code API](https://goqr.me/api/) – used for generating QR images




## How It Works 🔥

- User enters text or URL in the input box.
- On clicking the "Generate QR Code" button:
  - JavaScript fetches the text value.
  - It updates the `src` of an `<img>` tag using the [goqr.me API](https://goqr.me/api/).
  - The generated QR code is displayed dynamically.

---

## Future Enhancements 🚀

- Add **Download QR Code** button
- Add **Copy link** to clipboard
- Add **Dark/Light mode** switch
- Improve responsive design for mobile users



