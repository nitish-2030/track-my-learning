# 🚀 LearnFlow — Personal Learning Tracker

A minimal, fast, and distraction-free learning tracker built with plain HTML, CSS, and JavaScript. No frameworks, no backend, no setup — just open and start learning.

---

## ✨ Features

- **Skill + Topic Tracker** — Add any skill with its topics, mark them done in one tap
- **Auto Revision System** — Topics automatically get scheduled for revision at +2, +5, and +10 days after completion
- **Daily Log** — Quick one-line log to write what you learned each day
- **Streak Tracker** — Tracks how many days in a row you've studied 🔥
- **Progress Bar** — Visual progress for each skill
- **Dark / Light Mode** — Toggle with one click, preference is saved
- **Zero Setup** — No login, no server, no internet required after loading
- **Persistent Data** — All data saved in browser's localStorage, survives refresh and browser close

---

## 📱 How to Use

**Step 1** — Click `+ Add Skill` and enter a skill name with topics (comma separated)

**Step 2** — Tap any topic to mark it as done ✅

**Step 3** — Write a quick log of what you studied and hit Save

**That's it.** The app handles revision scheduling, progress tracking, and streaks automatically.

---

## 🗂️ Project Structure

```
/
├── index.html      ← entire app (HTML + CSS + JS in one file)
└── README.md
```

---

## 🌐 Deploying on GitHub Pages

1. Create a new GitHub repository
2. Upload `index.html` and `README.md`
3. Go to **Settings → Pages**
4. Under **Source**, select `main` branch and `/ (root)` folder
5. Click **Save**
6. Your app will be live at `https://yourusername.github.io/repo-name`

---

## 💾 Data & Storage

- All data is stored in **browser localStorage**
- Each device/browser has its own separate data
- Data is **permanent** — survives refresh, browser close, and device restart
- Only clears if you manually clear browser site data
- **Storage used:** ~25–30 KB per month of active usage (basically nothing)

---

## 🧠 Revision Logic

When you mark a topic as done, the app auto-schedules 3 revision reminders:

| Revision | When |
|----------|------|
| 1st | 2 days after completion |
| 2nd | 5 days after completion |
| 3rd | 10 days after completion |

These appear in the **Today's Revision** card automatically on the due date.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (custom, no frameworks) |
| Logic | Vanilla JavaScript |
| Storage | Browser localStorage |
| Fonts | Syne + Outfit (Google Fonts) |
| Hosting | GitHub Pages |

---

## 🔮 Future Plans

- [ ] Firebase sync (same data across devices)
- [ ] Google login
- [ ] Analytics dashboard
- [ ] Export/import data as JSON
- [ ] PWA support (install as app on phone)

---

## 📄 License

MIT License — free to use, modify, and share.

---

> Built for personal use. Simple by design. 🎯
