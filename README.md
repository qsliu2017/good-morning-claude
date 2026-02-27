# ⏰ Good morning, Claude

> Automatically keeps your Claude Code session windows alive on schedule — because you have a life, but also a cron job.

## Why does this exist?

Claude's subscription plan gives you a usage budget that resets every **5 hours**, starting from your first message. Miss the reset? Your window shifts. Your whole day shifts. Chaos.

So I mapped my day into 4 honest sessions:

| Window | Vibe |
|--------|------|
| 6am – 11am | ☕ Morning coffee. Pretend to be a morning person. |
| 11am – 4pm | 🍱 Lunch break productivity guilt. |
| 4pm – 9pm | 🔥 Peak hours. Actually getting stuff done. |
| 9pm – 2am | 🌙 *"I'm working late, 'cause I'm a coder."* |

The trick: send a dummy message at the start of each window to lock in the reset time. This repo automates that so you never have to think about it again.

---

## Setup

The easiest way is through Claude Code in your terminal:

```bash
/install-github-app
```

This sets up the GitHub App and walks you through adding `ANTHROPIC_API_KEY` as a repository secret. Follow the prompts — it takes about 2 minutes.

Alternative ways: see [claude-code-action/docs/setup.md](https://github.com/anthropics/claude-code-action/blob/main/docs/setup.md).

