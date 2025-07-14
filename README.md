# 💪 Bot-Discord-NNN – Your Accountability Buddy for No Nut November

**Bot-Discord-NNN** is a Python-based Discord bot designed to help users **track, survive, and conquer No Nut November (NNN)** by keeping tabs on streaks, sending motivation, and enabling optional anonymous logging.

---

## ✨ Features

- ⏱️ **Streak Timer** – Tracks how long you've stayed committed  
- 📬 **Daily Motivation** – Sends quotes, affirmations, or meme links  
- 🧠 **Anonymous Relapse Logging** – Log relapses privately (if enabled)  
- 🥇 **Leaderboard (Planned)** – Tracks top performers (opt-in only)  
- 🧘 **Tips & Support** – Offers coping mechanisms, tips, and routines

---

## 🛠 Tech Stack

- **Language:** Python  
- **Bot Framework:** [`discord.py`](https://discordpy.readthedocs.io/en/stable/)  
- **Database (Optional):** JSON / SQLite / Firebase (configurable)

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/theadhithyankr/Bot-Discord-NNN.git
cd Bot-Discord-NNN
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Add your bot token

Create a `.env` file in the root directory:

```env
DISCORD_TOKEN=your_discord_bot_token_here
```

### 4. Run the bot

```bash
python bot.py
```

---

## 🔄 Example Commands

| Command        | Description                           |
| -------------- | ------------------------------------- |
| `/start`       | Starts your NNN streak                |
| `/status`      | Shows your current streak duration    |
| `/relapse`     | Resets streak and logs (if enabled)   |
| `/motivate`    | Sends a random motivational message   |
| `/leaderboard` | Shows top streak holders (if enabled) |

---

## 🔧 Configuration (coming soon)

* Toggle anonymous logging
* Custom daily motivation source (API/local)
* Leaderboard opt-in/out
* Persistent storage options

---

## 📌 Roadmap

* [x] Basic streak tracking
* [x] Relapse handling
* [ ] Motivation scheduler (DM)
* [ ] Leaderboard & ranking system
* [ ] Admin dashboard (Flask/Streamlit)
* [ ] Mobile push notification integration

---

## 🤝 Contributing

1. Fork this repo
2. Create your feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add feature"`
4. Push and create a pull request

---

## 📄 License

MIT License — Use it, remix it, and ship it.

---

## 🧠 Built By

Made by [@theadithyankr](https://github.com/theadhithyankr)
Discipline is 🔑. This bot’s got your back.



