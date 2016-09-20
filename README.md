## Breakfast Bot

This is an slack bot to manage breakfast time (or as we call it, pitufo time) as breakfast time alerting, meals available, and automatic orders. This is just for learning whilst making team building. Feel free to contribute.

## Setting up

```
sbt run
```

## Publish


```
sbt universal:packageBin
# Go then to <root>/target/universal/breakfast-bot-<version>.zip
```

## Config file

Note: `application.conf` file under `src/universal/conf/` is packaged with the build. Use `src/main/resources/application.conf` for dev

The possible settings are:

    * token: The bot token as you get from slack
    * username: The bot username as you get from slack
    * message: The message the bot will send
    * users: The slack usernames to send the message to