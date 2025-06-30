# Twitter Media Downloader Bot
Telegram bot for downloading media from Twitter in best available quality. See here [@twitterimage_bot](http://t.me/twitterimage_bot)

## Usage
1. Clone repository
2. Set bot options in [config.py](https://github.com/skrimix/twitter_downloader_bot/blob/master/config.py)
3. `docker build -t twvid -f Dockerfile .`
4. `docker compose up -d`
5. Now you can use commands `/start`, `/help`, `/stats`, `/resetstats` or send tweet links
