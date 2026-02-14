# 🍽 Mise en Place — Family Meal Planner

A simple, beautiful weekly meal planner for families. Plan your week with drag-and-drop, auto-populated staples, AI-generated new dish ideas, shopping lists, and printable PDF exports.

## Features

- **Weekly calendar view** — 7 days left-to-right, drag meals between slots
- **Auto-populated staples** — your go-to dishes fill in automatically each week
- **AI dish generation** — get 10 new ideas tailored to your tastes (requires Anthropic API key)
- **Drag & drop or tap** — assign dishes to any day
- **Shopping list** — auto-generated from your week's plan, with checkboxes
- **PDF export** — print-friendly plan + shopping list + all recipes
- **Recipe viewer** — full ingredients with quantities (sized for 2 adults + 1 toddler) and steps
- **Preferences** — customize cuisines, dietary needs, allergies, cooking style
- **Week navigation** — move forward/backward between weeks
- **Persistent storage** — everything saved in your browser's localStorage

## Deploy to GitHub Pages (free hosting)

### Quick setup (5 minutes):

1. **Create a new GitHub repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it something like `meal-planner`
   - Make it **Public** (required for free GitHub Pages)
   - Check "Add a README file"
   - Click **Create repository**

2. **Upload the files**
   - In your new repo, click **Add file → Upload files**
   - Drag in `index.html` (and this `README.md` if you want)
   - Click **Commit changes**

3. **Enable GitHub Pages**
   - Go to **Settings → Pages** (in the left sidebar)
   - Under "Source", select **Deploy from a branch**
   - Set branch to `main` and folder to `/ (root)`
   - Click **Save**

4. **Access your site**
   - Wait 1-2 minutes for deployment
   - Your site will be at: `https://YOUR-USERNAME.github.io/meal-planner/`
   - Share this link with your wife!

### To enable AI dish generation:

1. Get an API key from [console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys)
2. In the app, go to **Shop & Manage → Preferences → Edit**
3. Paste your API key — it's stored only in your browser, never sent anywhere except Anthropic

### Notes

- All data is stored in your browser's localStorage — each device has its own data
- The app works great without an API key (just use staples + manually manage dishes)
- To share a week's plan, use the **Export PDF** button
