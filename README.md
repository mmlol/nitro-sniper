# Nitro Sniper [![CodeFactor](https://www.codefactor.io/repository/github/slow/nitro-sniper/badge)](https://www.codefactor.io/repository/github/slow/nitro-sniper) [![GitHub issues](https://img.shields.io/github/issues/slow/nitro-sniper?style=flat)](https://github.com/slow/nitro-sniper/issues) [![GitHub stars](https://img.shields.io/github/stars/slow/nitro-sniper?style=flat)](https://github.com/slow/nitro-sniper/stargazers)
Snipe nitro gift codes from alt accounts to your main account.

# Preview 
![Preview](https://i.imgur.com/PU3QaZc.png)
![Webhook](https://i.imgur.com/R9TQZ0k.png)

# Features
- Colours for your eyes to distinguish success and failure.
- Multi-token support.
- Mobile notifications work if you don't use your main token for sniping.
- Removes non-alphanumeric chars automatically from codes and tries to redeem.
- Auto-detects obvious fake codes.
- Light, no cluttered code, very simple and efficient.
- One-click deploy.
- Webhook support.

# Servers
- It is recommended to join servers from server sites such as disboard.
- If you have big servers over 50k, avoid a huge quantity of big servers as it can slow down the sniper due to it using a lot more memory for its cache.
- Recommended site: https://disboard.org/servers?sort=-member_count

# Installation methods
## ___Heroku (recommended)___
Click on the image below and login to continue the setup. 

##### After deploying, Go to the `Resources` tab and turn off the `web` dyno and turn on `worker`. Now you can go ahead and click on `More` in the top right and click on logs.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/slow/nitro-sniper/tree/main)  

## ___Local___
- Make sure [Node](https://nodejs.org/en/) is installed on your system and open a command prompt/terminal.
- Run `git clone https://github.com/slow/nitro-sniper nitro-sniper`
- Run `cd nitro-sniper`
- Run `npm install`
- Edit the dotenv file. <br>
    - To insert multiple tokens in the guildTokens variable, use `,` as a separator.<br>
    - Example: `token1,token2`
- Run `node .`

# Tips
- The less the latency to discord servers, the better; You could be competing with other snipers. <br>
    - High bandwidth hosting would benefit the sniper.
- There's a really high risk you might get terminated using this. <br>
    - Do not mention you have this anywhere. <br>
    - This is technically stealing money from discord.
