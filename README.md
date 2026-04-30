# Embedded Programming for Web Developers

A hands-on series teaching embedded programming to web developers. Interactive animations, real-world analogies, no electronics degree required.

## Posts

- **00: You Already Understand More Than You Think** — Microcontrollers, GPIO pins, voltage, resistors, and interrupts explained with interactive demos and web dev analogies.
- **01: CPUs and GPIO in Depth** — Registers, memory-mapped I/O, alternate functions, and what's happening at the hardware level.
- **02: Timers and PWM** *(coming soon)*
- **03: Talking to Other Devices** *(coming soon)*
- **04: Analog In, Analog Out** *(coming soon)*
- **05: Power, Sleep, and Battery Life** *(coming soon)*

## Hosting

This is a static site designed to be hosted on GitHub Pages.

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch**, select `main` and `/ (root)`
4. Your site will be live at `https://<username>.github.io/<repo-name>/`

## Structure

```
├── index.html              # Series landing page
├── assets/
│   ├── css/
│   │   └── shared.css      # Shared styles across all posts
│   └── js/
│       └── shared.js       # Shared scroll animations
├── posts/
│   ├── 00-you-already-understand.html
│   └── 01-cpus-and-gpio-in-depth.html
└── README.md
```

No build step. No dependencies. No frameworks. Just HTML, CSS, and vanilla JS.
