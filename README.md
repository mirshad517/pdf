# PDF Bot [@PDFStarkBot](https://t.me/PDFStarkBot)

> A star ⭐ from you means a lot to us!

<p align="center"><a href="https://www.github.com/StarkBotsIndustries/PDFBot"><img src="https://telegra.ph/file/71612596918ea10a776db.jpg" width="2000"></a></p>

Telegram bot with some PDF tools.

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

## Usage

### Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/mirshad517/pdf.git)

1. Tap on above button and fill `API_ID`, `API_HASH`, `BOT_TOKEN` (and `MUST_JOIN`).
2. Then tap "Deploy App" below it. Wait till deploying is complete (will take atmost 2 minutes).
3. After deploying is complete, tap on "Manage App"
4. Check the logs to see if your bot is ready!

### Local Deploying

1. Clone the repo
   ```markdown
   git clone https://github.com/StarkBotsIndustries/PDFBot
   ```
2. Get a DATABASE_URL. If you don't know how, deploy using Heroku Button only or delete database things as it's not a compulsion.
   
3. Edit `Config.py` and fill the needed variables

4. Enter the directory
   ```markdown
   cd PDFBot
   ```
5. Run the file
   ```markdown
   python3 bot.py
   ```

## Environment Variables

#### Mandatory Vars

- `API_ID` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `API_HASH` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)
- `DATABASE_URL` - Will be automatically added by Heroku.
- `MUST_JOIN` - Username/ID of your telegram channel/group.

## Functions

> More features soon if suggested by you :)
1) Rotate PDF Pages
2) Merge PDFs
3) Encrypt PDFs
4) Decrypt PDFs
5) Convert Images to PDF

## To-Do

> That's on you mainly...
- Watermark to PDFs
- Split PDFs

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

## Credits

- [Dan Tès](https://github.com/delivrance) for his [Pyrogram](https://docs.pyrogram.org) Library


## Support

Channel :- [@StarkBots](https://t.me/StarkBots)

Group Chat :- [@StarkBotsChat](https://t.me/StarkBotsChat)

## :)

[![ForTheBadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://github.com/StarkBotsIndustries)

[![ForTheBadge makes-people-smile](http://ForTheBadge.com/images/badges/makes-people-smile.svg)](https://github.com/StarkBotsIndustries)
