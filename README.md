# YTC-Server-Tools

A possible suite of tools for Discord server owners to advertise on YTC

## Ideas for development

- User adds bot to their server
- Server owner is messaged asking for consent
  > Consent could be granted in the form of a reaction on the message itself, from the owner of the server
  >
  > Could all be done in DMs
- Once consent is granted from the server owner, a new server invite is created and that link is sent in a private staff channel
  > Embed is also sent along with that invite link, with reactions allowing for anyone with the admin role or higher to approve the server
  >
  > The above-mentioned embed will contain the server link, the link will not appear in a separate message
- Once the server is approved, a category is created in the server in question containing an embed

  > The server owner and anyone with access to the private channel may react to the message to send an advertisement in YTC at a regulated interval (time limit for when server owners can send their server)

- When a server is denied, another embed is sent (like Anytime strike reason) allowing staff to send a reason to the server owner as to why their server was denied

  > The bot will automatically leave the server, but the owner can resubmit their server at any point

- There **WILL** be a manual blacklist that YTC managers can add servers' ids to, preventing the bot from interacting or sending any related messages about servers on said list.
  > Command like `!blacklist [serverID]` would be useful to prevent spammers and repeat offenders of denial-worthy guidelines.
