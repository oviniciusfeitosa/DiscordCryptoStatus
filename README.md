# DiscordCryptoStatus

This bot will update its status message with the current price of the desired cryptocurrency.

![Example bot setup.](https://i.imgur.com/aDy2dpj.png)

## How to use

This bot is really easy to use.

Just follow these steps:
1. Have [Node.JS](https://nodejs.org) installed
2. Clone this repository to a folder on your computer
3. Open a terminal in that folder, and install the packages with `npm install`
4. Open the `.env-template` file and configure it to your liking
5. Access [here](https://discord.com/developers/applications) and create a New Application
6. Get the application ID to fill URL bellow
6. Get the Server ID from your server by right click then `Copy ID`. Set `SERVER_ID` environment with this value.
7. Select **Bot** Tab then **Add Bot**
8. Now copy the token and set the `DISCORD_TOKEN` environment
9. Access the url replacing the fields `https://discord.com/api/oauth2/authorize?client_id=xxxxxxx&permissions=0&scope=bot%20applications.commands`

For information on getting a bot token, follow the steps on [the Discord developer documentation.](https://discordapp.com/developers/docs/intro)

## Extra Info

This was created for my Discord server, but I wanted to share it with added flexibility for anyone to use.

This relies on the API hosted at https://api.coingecko.com

## References

- [Cryptocurrency-Status-Discord-Bot](https://github.com/cferreras/Cryptocurrency-Status-Discord-Bot)
- [Minecraft Player Count Discord Bot](https://github.com/SpencerTorres/Minecraft-Player-Count-Discord-Bot)
- [CoinGecko API price example](https://api.coingecko.com/api/v3/coins/hero-cat-token)