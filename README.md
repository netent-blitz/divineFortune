# Netent Blitz player
Open-source Netent Blitz implementation

Blitz is a technology introduced by HeroGaming casinos, which allow to play sugnificantly faster selected Netent games. It was approved and supported by Netent officials.
More info [here](https://herogaming.com/news/hero-gaming-launches-blitz-a-faster-way-to-play-casino/)

I have decided to make open-source implementation of this technology, building it from scratch by reverse-engineering http requests, sent by slot interface.

# Supported games
* Divine Fortune
* more to come...

# How to use
Authorize at your casino account and open "Divine Fortune" slot.
Right click on Slot and select "This Frame" -> "Open frame in new window".
Ne window URL should start with "https://****-static.casinomodule.com/", it contains your personal account information, necesssary to play game on your account.
Copy/paste that URL to "Game URL" input field and click "Start play".

**Check with minimal bets, that everything is working as you expected!**

All spins will be played from your account and you are responsible for any losses and wins which might occur.

Have fun.
