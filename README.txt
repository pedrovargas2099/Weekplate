WeekPlate: install on your phone (and your wife's)
===================================================

What it is: a dinner planner and grocery list that lives entirely on your phone.
No account, no server, no ads. Works offline once installed.

OPTION A: try it in one minute (data may not persist)
  1. Send WeekPlate.html to your phone and open it with Chrome.
  2. Good for a first look. Chrome may not keep your settings for files opened
     this way, so use Option B for daily use.

OPTION B: install it like an app (recommended)
  1. Put this whole folder on any free static host with https
     (Netlify, GitHub Pages, Cloudflare Pages). It is just files; there is nothing to run.
  2. On each phone, open the link in Chrome.
  3. Chrome menu (three dots) > Install app (or Add to Home screen).
  4. It now has an icon, opens full screen, and works offline.

Using it
  - Setup asks about your store, household, nights, pantry, diet, equipment and dislikes.
  - Home: this week's dinners. Swap changes one night. Open a recipe, tap "I cooked it".
  - Grocery: a list with real pack sizes ("buy 1 x 12", "9 left over").
    Tap any price to type what you actually paid at that store. It is saved per store and used from then on.
    Until you enter one, prices are rough estimates and say so.
  - Compare stores: same list priced at every store, using your prices where you have them.
  - Share list: sends the grocery list as text (to your wife, for example).
  - Recipes: 30 built in. "+ Add your own" takes ingredients one per line ("1.5 lb chicken thighs").
  - You > Copy my data, then paste it on the other phone under "Load pasted data" to move or back up everything.

Notes
  - Your data stays on that phone's browser. Clearing site data erases it, so use Copy my data now and then.
  - To update the app after changing files on the host, change 'weekplate-v1' in sw.js to a new name.
  - Allergy filters are preferences, not guarantees. Read labels.
