# A6 Ministry and Media — Discord Server Builder

This project is a Node.js tool (discord.js v14) that automatically creates a fully structured Discord server called **“A6 Ministry and Media.”** It’s designed for Catholic diaconal ministry, study, and digital outreach.

**What it sets up**
- Preconfigured roles: Deacon/Chaplain, Clergy, Moderators, Seminarians, Faithful, Guests
- Categories & channels for prayer, catechesis, apologetics, fellowship, and outreach
- A Chant Bot area with `#chant-control` and a **Chant Room** voice channel for continuous Gregorian chant
- Channels prepared for daily Scripture verses and daily prayers

## Tech
- Node.js (LTS)
- discord.js v14
- dotenv

## Quick start
```bash
# 1) Clone
git clone https://github.com/<YOUR-USER>/a6-ministry-media-discord-builder.git
cd a6-ministry-media-discord-builder

# 2) Install
npm install

# 3) Create .env with your bot token
echo DISCORD_TOKEN=YOUR_BOT_TOKEN_HERE > .env

# 4) Run (creates a new Discord server with the full structure)
node build-a6.js
