# Evening Planner

A one-page planner and tracker for the 9:30–11:30 PM post-bedtime block. It needs no build step, server or accounts: it's one `index.html`.

## Put it on GitHub Pages (about 5 minutes)

1. On github.com, click **New repository** and name it something like `evening-planner`. Public is the simplest choice, since Pages on a private repo needs a paid plan.
2. Click **Add file → Upload files**, drag in `index.html` (and this README), then **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment*, set **Source: Deploy from a branch**, **Branch: `main` / `(root)`**, then **Save**.
4. After about a minute your site is live at `https://<your-username>.github.io/evening-planner/`.
5. On your phone, open that URL and choose **Share → Add to Home Screen** so it works like an app.

To change the code later, edit `index.html` on GitHub (pencil icon) or upload a new version. Pages redeploys on every commit.

## How it works

- **Tonight**: enter when bedtime actually ended and every start time recalculates. *Auto-fit* shrinks flexible items so you still finish by lights-out. **Protected** items (the 32nd-note runs) and **fixed-time** items (the Wednesday Preply lesson) never shrink. Tap ✓ to log an item, *Skip* to drop it for the night only, and rate your energy from 1 to 5. Fitness items have a workout picker: tap the type (the day's planned type is outlined with a dashed border) and note what you did. Choosing a type fills in what you did last time for that type, so a repeat workout takes one tap.
- **Progress**: streak (nights with at least 50% of planned minutes done), weekly completion, average bedtime-wrap time, average energy, minutes per focus area against the weekly plan, an 8-week heatmap, workouts by type over the last 30 days, a workout log and recent notes.
- **Edit schedule**: add, remove, reorder and retime activities for each day; copy one day to others; rename focus areas; change the default start and lights-out times; edit the house rules. Set each fitness night's planned workout type, and edit the list of workout types under Defaults & rules.

## Your data

Your schedule and history are saved in your browser's local storage on each device. They are not stored in the repo, so they stay private even if the repo is public. To move data between your laptop and phone, or to back it up, use **Edit schedule → Backup**: Copy or Download the export, then Import it on the other device.
