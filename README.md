# brat

A dead-simple, fullscreen **live message** webapp — type and it fills the screen, huge.

- Auto-fits text to a square box (scales font down as you type more)
- **bratgenerator-style** justified spacing (`text-align-last: justify`) + blur
- White / brat-green / inverted color modes
- Self-hosted Arial Narrow so phones render the same face as desktop

## Mobile
On phones and tablets a button bar replaces the shortcuts — brat, invert, blur,
full, save, clear — sized for thumbs and riding above the on-screen keyboard.
Tap anywhere to start typing. Save goes through the native share sheet. The
eye in the top right hides the controls for a clean shot; the chrome also fades
on its own after a couple of idle seconds and comes back on any tap.

Colour modes wipe in as a circle from the button you pressed, buttons ripple
and spring, blur eases, and clearing blurs the text out.

## Shortcuts
- `Tab` — fullscreen
- `⌘/Ctrl + B` — brat green
- `⌘/Ctrl + Enter` — invert
- `⌘/Ctrl + K` — toggle blur
- `Esc` — clear

It's a single static `index.html`, no build step. Deployed on Vercel → [brat.safzan.dev](https://brat.safzan.dev).
