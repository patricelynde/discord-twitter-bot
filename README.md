# Discord Twitter Bot

### Description

Discord bot that allows you to follow twitter user, then sends any tweets to a specific Discord channel.

### Installing

```shell
npm i
```

### Configuration

Create a `.env` file (or as environment variables) at the root of the repository with those keys from the Twitter API and the discord API:
```
CONSUMER_KEY=
CONSUMER_SECRET=
ACCESS_TOKEN_KEY=
ACCESS_TOKEN_SECRET=
DISCORD_TOKEN=
```

### Dependencies

```json
dependencies: {
    "discord.io": "github:izy521/discord.io",
    "dotenv": "^6.1.0",
    "express": "^4.16.4",
    "twit": "^2.2.11",
    "winston": "^3.1.0"
}
```
