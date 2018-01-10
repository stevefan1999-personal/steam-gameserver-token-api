# Steam Gameserver Token Util

A commandline utility for managing Steam Gameserver Tokens through Steam Web API.

Its primary target is the IGameServersService Interface, and the code has been built on knowledge from two sources.  
A [community made API reference](http://steamwebapi.azurewebsites.net/).  
And the [Steamworks Documentation Website](https://partner.steamgames.com/doc/webapi/IGameServersService).

It currently outputs all returned API JSON data as unquoted Semicolon Separated Values with Headers.

The Utility currently supports three features.

* Create new Gameserver Account with accompanying Token
* List Gameserver Accounts
* Delete Gameserver Account by ID (SteamID)

If the utility receives an X-error_message Response Header, it will log the message to console, and exit.
