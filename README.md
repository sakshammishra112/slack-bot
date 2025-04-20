# 🎂 Slack Age Bot

A simple Slack bot built with Go that calculates your age based on your year of birth.

## 🚀 Features

- Responds to the command:  "my yob is year"
and replies with your age.

- Logs command events for basic analytics.

## 🛠️ Requirements

- Go 1.18+
- Slack Bot & App Tokens

## ⚙️ Setup

Clone the repo, set up your environment variables, and run the bot:

```bash
git clone https://github.com/sakshammishra112/slack-bot.git
cd slack-bot

export SLACK_BOT_TOKEN='xoxb-your-bot-token'
export SLACK_APP_TOKEN='xapp-your-app-token'

go run main.go
