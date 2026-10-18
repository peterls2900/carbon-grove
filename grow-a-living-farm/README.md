# Grow a living farm

A touch-friendly educational game that shows coffee and cattle farmers the benefits of agroforestry. Built for iPad (Safari, landscape) at farmer fairs and cooperative events.

Players plant shade, fruit, fodder and timber trees, then grow their farm through 8 years of weather and market events, side by side with a neighbour who plants no trees.

## Play it

Open `index.html` in any modern browser. No build step or server is needed.

## Publish with GitHub Pages

1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under "Build and deployment", choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute the game is live at `https://<your-org>.github.io/<repo-name>/`.

On the iPad, open that link in Safari and choose **Share → Add to Home Screen** so it runs full screen like an app.

## Kiosk behaviour

- Returns to the start screen after 2.5 minutes without a touch (`IDLE_MS` in the script).
- Pinch and double-tap zoom are blocked.
- Works offline once loaded; fonts fall back to system fonts if there is no connection.

## Editing the game

All numbers and texts sit at the top of the `<script>` block in `index.html`:

- `FARMS` — tree types, costs, income, shade, carbon and the tips shown when a tree is selected.
- `EVENTS` — yearly events, how hard they hit, and the fact shown after each year.
- `START_CASH`, `YEARS` — starting money and game length.

## What the game measures

Money tab: profit, money in the bank, coffee (or milk and cattle) income, fruit and tree income, fertiliser cost, pesticide (or tick and fly treatment) cost.

Farm health tab: coffee quality (or herd condition), soil health, soil moisture, wildlife, resilience, carbon stored.

The model is illustrative, not a forecast. Review the figures and fact texts with your agronomy team before using it with farmers.

---

Made by GrowGrounds — [growgrounds.org](https://growgrounds.org)
