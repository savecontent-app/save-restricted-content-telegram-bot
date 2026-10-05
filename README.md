# SaveContent: save restricted content from Telegram

**SaveContent** is a Telegram bot that saves posts from channels and groups where saving and forwarding are switched off, downloads stories, and keeps the messages people delete or edit in your private chats.

- Bot: [@SaveContent_resRoBot](https://t.me/SaveContent_resRoBot)
- Website and guides: [savecontent.app](https://savecontent.app)

There is nothing to install and nothing to host. You send a link, the bot sends the post back.

## What it does

| Feature | How |
|---|---|
| Save restricted posts (video, photo, file, text) | Send the post's link: `t.me/channel/123` |
| Save several posts at once | Send a range: `t.me/channel/100-110` |
| Save from private channels | Log in once with your own account, then send `t.me/c/123456/789` |
| Download stories | Send `@username` or a story link `t.me/username/s/123` |
| See deleted messages | Connect the bot in Telegram Settings > Chat Automation |
| See the original of edited messages | Same connection |
| Keep view-once photos and videos | Reply to the message before opening it |

Public channels work without logging in, even when saving is restricted. Business features work through Chat Automation and do not need Telegram Premium.

## Save a restricted post in three steps

1. In Telegram, open the post, tap Share, then Copy link.
2. Send the link to [@SaveContent_resRoBot](https://t.me/SaveContent_resRoBot).
3. The bot sends you the video, photo or file as a normal message.

Full guide: [How to save restricted content from Telegram](https://savecontent.app/save-restricted-content/)

## Guides

- [How to save restricted content from Telegram](https://savecontent.app/save-restricted-content/)
- [See deleted and edited Telegram messages](https://savecontent.app/deleted-messages/)
- [Save view-once photos and videos](https://savecontent.app/view-once/)
- [Download Telegram stories](https://savecontent.app/stories/)
- [Ways to save restricted Telegram content, compared](https://savecontent.app/compare/)
- [FAQ](https://savecontent.app/faq/)
- [Security and privacy](https://savecontent.app/security/)

Also available in [العربية](https://savecontent.app/ar/), [فارسی](https://savecontent.app/fa/), [Русский](https://savecontent.app/ru/), [Bahasa Indonesia](https://savecontent.app/id/) and [Türkçe](https://savecontent.app/tr/).

## Why not a self-hosted bot?

Open-source "save restricted content" bots give you full control, but you need a server, Telegram API keys, a session string, and you keep it updated yourself. SaveContent is the hosted alternative: the same result from your phone, with no setup. The trade-off is trust, so the site says exactly what is stored and how to end the session: [savecontent.app/security](https://savecontent.app/security/).

## Limits

- It saves what your own account can already see. It cannot open a private channel you are not a member of.
- Messages deleted before you connected the bot cannot be recovered. Nobody can do that.
- The free plan has a daily number of saves and a short wait between them. Paid plans raise both.
- Groups, channels and secret chats are not covered by the deleted-messages feature. Telegram only passes private chats to Chat Automation bots.

## Fair use

A restriction is usually there because the author wants control over their work. Save posts for your own use and do not re-publish other people's content as yours.

## About this repository

This repository holds the documentation for the SaveContent bot. The bot itself is a hosted service and its source code is not published here. For questions, write to the bot: your message reaches support.

SaveContent is an independent service. It is not affiliated with, endorsed by or operated by Telegram.
