# Corlys Privacy Policy

**Effective date:** November 18, 2026

This policy explains what information the Corlys Discord bot ("Corlys", "the bot"), operated by Warner Bros. Games Boston ("we", "us"), uses and why.

## Information Corlys uses

Corlys only accesses information that Discord provides to bots through its API, in servers where Corlys is active:

- **Server members:** user ID, username, roles, the date you joined the server, and Discord's safety signals ("Unusual Account Activity" and "Unusual DM Activity").
- **Messages in designated support channels:** message ID, author, timestamp, and whether the message is pinned or started a thread. Corlys does not read message text for these actions.
- **Messages in designated invite-sharing channels:** message ID, author, timestamp, whether the message is pinned, and the message text, including embeds. Corlys reads the text only to find Discord invite links and checks each invite with Discord to see whether it is still valid. This requires Discord's Message Content Intent and applies only to these channels.
- **Server settings:** roles, channels, and security action settings needed to perform its tasks.

Corlys does not read direct messages and does not access the contents of threads.

## How the information is used

The information is used only to:

- Keep the server's "Pause DMs" security action enabled.
- Decide which support channel messages to delete.
- Delete messages in invite-sharing channels that contain no Discord invite link, or only expired invite links.
- Decide whether to ban a flagged member, and post a record of the ban (user ID, the signal, and the action taken) in a moderation channel visible to server staff.

## Storage and retention

Corlys does not keep a database. It runs as scheduled jobs on GitHub Actions. Each run's log, which can include usernames, user IDs, the actions taken, and short excerpts of messages that were or would be deleted, is stored by GitHub in a private repository and is automatically deleted after GitHub's log retention period (90 days by default). Ban records posted in moderation channels remain in Discord until server staff delete them.

## Sharing

We do not sell, rent, or share this information with third parties. It is processed by Discord and GitHub as part of operating the bot, under their own privacy policies: [Discord Privacy Policy](https://discord.com/privacy) and [GitHub Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

## Your choices

- Leaving a server where Corlys is active stops Corlys from processing your information in that server.
- To ask about information related to you, or to request deletion of ban records or logs that mention you, contact us through [https://appeal.gg/gotdragonfire](https://appeal.gg/gotdragonfire) or [https://appeal.gg/gotconquest](https://appeal.gg/gotconquest).

## Changes

We may update this policy at any time. The effective date above shows when it was last changed.

## Contact

Questions about this policy: [https://appeal.gg/gotdragonfire](https://appeal.gg/gotdragonfire) or [https://appeal.gg/gotconquest](https://appeal.gg/gotconquest)
