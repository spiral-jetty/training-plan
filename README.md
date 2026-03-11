# Race Training Plan

A fully interactive, single-file training plan tracker built for runners. No account, no app, no server — just open the HTML file in any browser and start planning.

**[→ Open the planner](https://yourusername.github.io/your-repo-name)** *(update this link after you publish)*

---

## Features

- **8-week template** — structured around base building, pace work, taper, and race week. Fully customizable.
- **Drag to rearrange** — move activity tiles between days, or drag entire weeks to reorder them
- **Add & edit activities** — change type, update notes, bold key text, add multiple workouts per day
- **Custom activity types** — add rock climbing, swimming, cycling, or anything else alongside the built-ins
- **Editable header** — click the title, dates, goal time, target pace, and race type to customize everything
- **Race type dropdown** — 5K through Marathon; updates the title automatically
- **Live stats** — Race Date, Goal Time, Peak Long Run, and Cross-Training all update as you edit
- **Check off days** — mark days complete with a progress bar tracking your whole plan
- **Save as PDF** — clean printable layout (landscape A4)
- **Backup & restore** — download a `.json` backup, restore it on any device or browser
- **Auto-saves** — all changes save automatically in your browser's local storage
- **Mobile friendly** — works on phones and tablets

---

## How to use

### Option 1: GitHub Pages (recommended)
1. Fork or clone this repo
2. Rename `index.html` if needed
3. Go to **Settings → Pages** → set source to `main` branch, root folder
4. Your plan will be live at `https://yourusername.github.io/your-repo-name`

### Option 2: Local file
Just download `index.html` and open it in any browser. Everything works offline except the Google Fonts (which fall back gracefully).

### Option 3: Share with a friend
Send them the `index.html` file. They'll start with the default blank template. If you want them to see *your* plan and progress, click **Save backup** first and send them both files — they can click **Restore backup** to load your version.

---

## Customizing your plan

| What | How |
|------|-----|
| Plan title | Click the title at the top |
| Dates, goal, target pace | Click any of the header fields |
| Race type | Use the dropdown (5K → Marathon) |
| Week theme | Click the theme text next to the week number |
| Week mileage | Click the mileage badge |
| Activity notes | Hover a tile → click the pencil icon |
| Activity type | Hover a tile → pencil → pick a new type |
| Add a workout | Click **+ Add** at the bottom of any day |
| Move a workout | Drag a tile to another day |
| Reorder weeks | Hover a week → drag the grip handle on the left |
| Add a week | Click **Add Week** at the bottom |
| Custom activity type | Open any tile editor → click **New type…** |

---

## Tech notes

- Pure HTML/CSS/JS — zero dependencies, zero build step
- Data persists via `localStorage` (browser-specific)
- Fonts loaded from Google Fonts (Inter + IBM Plex Mono)
- Print stylesheet included for clean PDF export

---

## License

MIT — do whatever you want with it.
