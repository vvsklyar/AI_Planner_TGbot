# AI_Planner_TGbot
A lightweight Telegram bot for mindful daily and weekly planning, personal reflection, and progress tracking
Designed to guide users through structured rituals similar to coaching self-inquiry.

## ✨ Features

- `/start` — Welcome message with usage instructions
- `/utro` — Morning planning ritual (daily priorities and focus)
- `/vecher` — Evening reflection ritual (review and gratitude)
- `/nedelya` — Weekly reflection and next-week setup (combines overview + intention setting)
- Step-by-step question prompts with summarized recap at the end

## 🛠️ Tech Stack

- Python 3
- [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)

## 🚀 Getting Started

### 1. Create a Telegram Bot
- Go to [@BotFather](https://t.me/BotFather) in Telegram
- Run `/newbot` and follow instructions
- Save your bot token

### 2. Clone the Repo and Set Environment
```bash
git clone https://github.com/your-username/telegram-reflection-bot.git
cd telegram-reflection-bot
```

### 3. Install Dependencies
```bash
pip install python-telegram-bot
```

### 4. Set Token and Run
```bash
export TELEGRAM_BOT_TOKEN=your_token_here
python main.py
```

## 📋 Rituals Overview

### Morning Ritual `/utro`
- Urgent tasks
- Strategic focus
- What to skip today
- Inspiration & mission
- Body & mental state check-in

### Evening Ritual `/vecher`
- Achievements
- Emotions
- Gratitude
- Support shared
- Tomorrow’s preview

### Weekly Ritual `/nedelya`
**Part 1: Weekly Review**
- Completed items
- Challenges
- Insights
- Overload moments
- Letting go
- Gratitude

**Part 2: Weekly Setup**
- Main directions & projects
- 1 step per project
- Inspiration
- Desired state
- Key relationships
- Simplifications
- Weekly intention

## 📌 Roadmap
- [ ] Data persistence (Google Sheets / Notion)
- [ ] Scheduled reminders
- [ ] Web UI dashboard
- [ ] Custom rituals per user

## 🙌 Contributing
Pull requests welcome. For major changes, open an issue first.

## 📄 License
MIT
