# Car Hacking Village

Landing page for the **Car Hacking Village** — a hands-on workshop where attendees inject CAN frames into a bench-mounted VW Group instrument cluster (Škoda Fabia, SEAT Ibiza, SEAT Leon, ~2010) using a USB-to-CAN adapter (CANable 2.0 / SH-C31A) driven entirely in the browser via **WebUSB**. Run at events including BSides Groningen, BSides Luxembourg, and OrangeCon.

The page walks visitors through the setup, wiring, and challenges, and links to the companion WebUSB CAN console at <https://roaldnefs.github.io/webusb-can/>.

## Local preview

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

> **Note:** WebUSB requires Chromium-based browsers (Chrome 61+ / Edge 79+). Firefox and Safari are not supported by the linked CAN console.
