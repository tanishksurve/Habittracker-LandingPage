# Habit Streak Landing Page

A single-page marketing site for a habit-tracking app that uses Tailwind CSS (via CDN) with a small custom configuration and minimal custom styles.

## Getting Started

1. Open `index.html` in your browser. No build step is required.
2. Ensure `styles.css` and `main.js` are in the same directory as `index.html` so they load correctly.

## File Structure

- `index.html` — Page markup and Tailwind utility classes.
- `styles.css` — Minimal custom CSS helpers (e.g., perspective utility).
- `main.js` — Tailwind CDN configuration (colors, fonts, radii).

## Customization

- Update theme colors or fonts in `main.js` under `tailwind.config`.
- Add additional custom CSS in `styles.css` if you need utilities that Tailwind doesn’t cover.

## Notes

- Tailwind is loaded from the CDN; an internet connection is required to fetch the library and Google Fonts.
- The page supports light and dark modes via the `dark` class on the root `<html>` element.

