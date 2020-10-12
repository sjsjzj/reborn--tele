# <a Tele-rebo - Telegram 

<p align="left">
    <a href="https://t.me/https://t.me/telelrebo"> <img src="https://img.shields.io/badge/telegram-Support_Group-blue?style=@telerebox=telegram" alt="Support" /></a>
    <a href="https://github.com/telelrebo/telerebo/stargazers"><img src="https://img.shields.io/github/stars/telelrebo/telerebo?style=social"></a>
    <a href="https://github.com/telelrebo/telelrebo"><img src="https://img.shields.io/github/last-commit/telersbo/telelrebo?style=flat-square"></a>
</p>
    
## Video Tutorial on deploying

Click the below button to watch the video tutorial on deploying

"(https://youtu.be/e4vINpXenbQ)" الفيديو التعليمي
   
## The Easier Way to install

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/xditya/TeleBot)

## Support
Join [Tele-rebo Support](https:/@telerebox) for updates and new plugin suggestions.
Do fork and star the repo 

### Session String 
<a href="https://telebot-sessionstring-generator.xditya.repl.run/" target="_blank"><img src="https://img.shields.io/badge/run-string__session.py-red?style=for-the-badge&logo=repl.it" alt="generate_string" /></a>

### The Normal Way

Simply clone the repository and run the main file:
```sh
git clone https://github.com/xditya/TeleBot
cd TeleBot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create local_config.py with variables as given below>
python3 -m userbot
```

An example `local_config.py` file could be:

**Not All of the variables are mandatory**

__The Userbot should work by setting only the first two variables__

```python3
from heroku_config import Var

class Development(Var):
  APP_ID ="(ضع الايبي ايدي)" 
  API_HASH = "(ضع الايبي شن)" 
```

### UniBorg Configuration

The UniBorg Config is situated in `userbot/uniborgConfig.py`.

**Heroku Configuration**
Simply just leave the Config as it is.

**Local Configuration**
Check [Line 111](https://github.com/Total-Noob-69/X-tra-Telegram/blob/master/userbot/uniborgConfig.py#L111) and start adding your vars there.
Fortunately there are no Mandatory vars for the UniBorg Support Config.

## Mandatory Vars

- Only two of the environment variables are mandatory.
- This is because of `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`
    - `APP_ID`:    تستطيع جلبه من هنا https://my.telegram.org
    - `API_HASH`:    تستطيع جلبه من  https://my.telegram.org
    -  `ENV`:                تستطيع  جليه من  https://generatestringsession.sandeep1709.repl.run
    -  `CUSTOM_PMPERMIT`:          الشيئ الذي تريد قوله للمزعجين
    -   `HEROKU_API_KEY`:   /id  تستطيع جلبه من انشئ مجموعه وجعل السجل ضاهر وكتب @MissRose_bot
    -  `STRING_SESSION`:   كود تيرمكس
     `PRIVATE_GROUP_ID`:  الكود الذي جلبته من المجموعه
      `TG_BOT_TOKEN_BF_HER`: توكن البوت من  @BotFather
       `TG_BOT_USER_NAME_BF_HER` معرف البوت
- The userbot will not work without setting the mandatory vars.

# Disclaimer
```
/**
    Improper use may lead to ban.
    I am not responsible if you misuse this bot.
	This bot is just for managing groups more effectively and having some fun
	with your telegram account.
	No one is responsible for your actions.
	If you spammed and got reported again and again, 
	and, at last got your account banned, and you
	point your fingers at me, I'll be rolling on the floor laughing at you.
/**
```


