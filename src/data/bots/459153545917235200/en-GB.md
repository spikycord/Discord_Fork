---
description: A simple utility bot, with fun commands.
name: Chat Noir
---

<style>
h2 {
    color: black;
}
table, th, td {
    border: 1px solid black;
    border-collapse: collapse;
}
th, td {
    padding: 5px;
}
</style>
Chat Noir is a fun, moderation, and utility and open sourced discord bot.

The default prefix is <code>cn.</code> This can be changed by running the <strong>prefix</strong> command.

Argument help:
[] - Means the argument is optional and is not required.

<> - Means the argument is not optional and is required.

《alias1|alias2》 - Meaning you can choose from alias1 or alias2

<subCommand1|subCommand2|subCommand3:string> - If you choose the third sub command it will be based off the input
example: r.tag memes

Permission level help:

0 - Anyone can use the command. Requires no permissions.

6 - Requires the permission Kick Members.

7 - Requires the Administrator permission.

8 - Requires you to be the owner of the server.

10 - Bot owner

<h2>Command Categories</h2>

• [General Commands](#jumpLinkGeneral)

• [Configuration Commands](#jumpLinkConfiguration)

• [Fun Commands](#jumpLinkFun)

• [Music Commands](#jumpLinkMusic)

• [Utility Commands](#jumpLinkUtility)

• [Idiotic Commands](#jumpLinkIdiotic)

<h2 id="jumpLinkGeneral">General Commands</h2>
<table><tr><th scope="col">Command</th><th scope="col">Description</th><th scope="col">Aliases</th><th scope="col">Permission Level</th><th scope="col">Usage</th>
<tr><th scope="row"><strong>help</strong></th><td>Display help for a command.</td><td>commands</td><td>0</td><td>r.《help|commands》 [command]</td></tr>
<tr><th scope="row"><strong>invite</strong></th><td>Invite or join the support server... What else?</td><td></td><td>0</td><td>r.invite</td></tr>
<tr><th scope="row"><strong>ping</strong></th><td>Ping pong?</td><td></td><td>0</td><td>r.ping</td></tr>
<tr><th scope="row"><strong>stats</strong></th><td>Provides details about the bot.</td><td></td><td>0</td><td>r.stats</td></tr>
<tr><th scope="row"><strong>info</strong></th><td>Provides info about the bots framework.</td><td></td><td>0</td><td>r.info</td></tr>
<tr><th scope="row"><strong>invite</strong></th><td>Invite the bot to your server.</td><td></td><td>0</td><td>r.invite</td></tr>
</table>

<h2 id="jumpLinkConfiguration">Configuration Commands</h2>
<table><tr><th scope="col">Command</th><th scope="col">Description</th><th scope="col">Aliases</th><th scope="col">Permission Level</th><th scope="col">Usage</th>
<tr><th scope="row"><strong>logs</strong></th><td>Allows you to enable/disable mod log settings.</td><td>mlogs, modlogs</td><td>7</td><td>r.《logs|mlogs|modlogs》 <enable|disable|channel> [args]</td></tr>
<tr><th scope="row"><strong>prefix</strong></th><td>Allows you to change the bots prefix for your server.</td><td></td><td>7</td><td>r.prefix <newPrefix></td></tr>
<tr><th scope="row"><strong>raw</strong></th><td>Returns the guilds config in a JSON format.</td><td>rawconf, rawconfig</td><td>0</td><td>r.《raw|rawconf|rawconfig》</td></tr>
<tr><th scope="row"><strong>starboard</strong></th><td>Allows you to change the limit or channel of the starboard.</td><td>sboard</td><td>7</td><td>r.《starboard|sboard》 <limit|channel> [args]</td></tr>
<tr><th scope="row"><strong>welcomes</strong></th><td>Allows you to enable or disable welcomes and set welcome/leave message.</td><td></td><td>7</td><td>r.welcomes <enable|disable|channel> [args]</td></tr>
</table>

<h2 id="jumpLinkFun">Fun Commands</h2>
<table>
<tr><th scope="col">Command</th><th scope="col">Description</th><th scope="col">Aliases</th><th scope="col">Permission Level</th><th scope="col">Usage</th>
<tr>
<tr><th scope="row"><strong>meme</strong></th><td>Gets a meme from a meme for you :)</td><td>m3m3, memeplox</td><td>0</td><td>r.《meme|m3m3|memeplox》</td></tr>
<tr><th scope="row"><strong>software</strong></th><td>Gets a random post from r/softwaregore</td><td>softwaregore, rsoftwaregore</td><td>0</td><td>r.《software|softwaregore|rsoftwaregore》</td></tr>
</table>

<h2 id="jumpLinkMusic">Music Commands</h2>
<table>
<tr><th scope="col">Command</th><th scope="col">Description</th><th scope="col">Aliases</th><th scope="col">Permission Level</th><th scope="col">Usage</th>
<tr>
<tr><th scope="row"><strong>lastskip</strong></th><td>Skips to the last song in the queue.</td><td></td><td>0</td><td>lastskip</td></tr>
<tr><th scope="row"><strong>loop</strong></th><td>Loops the current song.</td><td>repeat, togglerepeat, toggleloop</td><td>0</td><td>r.《loop|repeat|togglerepeat|toggleloop》</td></tr>
<tr><th scope="row"><strong>lyrics</strong></th><td>Gets lyrics about a specific song or the current playing one.</td><td>lyric</td><td>0</td><td>r.《lyrics|lyric》 [query]</td></tr>
<tr><th scope="row"><strong>nowplaying</strong></th><td>Gets info on the current playing song.</td><td>np, nowp, nplay</td><td>0</td><td>r.《nowplaying|np|nowp|nplay》</td></tr>
<tr><th scope="row"><strong>play</strong></th><td>Plays a song in a voice channel.</td><td></td><td>0</td><td>r.play <query></td></tr>
<tr><th scope="row"><strong>queue</strong></th><td>Loops the current song.</td><td>songs, tracks</td><td>0</td><td>r.《queue|songs|tracks》</td></tr>
<tr><th scope="row"><strong>skip</strong></th><td>Skips to a specific song or the next song.</td><td></td><td>0</td><td>r.skip</td></tr>
<tr><th scope="row"><strong>stop</strong></th><td>Stops the current song.</td><td></td><td>0</td><td>r.stop</td></tr>
</table>

<h2 id="jumpLinkUtility">Utility Commands</h2>
<table>
<tr><th scope="col">Command</th><th scope="col">Description</th><th scope="col">Aliases</th><th scope="col">Permission Level</th><th scope="col">Usage</th>
<tr>
<tr><th scope="row"><strong>afk</strong></th><td>Sets or removes you from the afk status.</td><td>setafk, afkstatus</td><td>0</td><td>r.《afk|setafk|afkstatus》 <set|remove> [args]</td></tr>
<tr><th scope="row"><strong>color</strong></th><td>It gets a color... What else?</td><td>colour</td><td>0</td><td>《color|colour》 <color></td></tr>
<tr><th scope="row"><strong>remind</strong></th><td>Sets a reminder for you.</td><td>remindme, setreminder</td><td>0</td><td>r.《remind|remindme|setreminder》 <when> <text></td></tr>
<tr><th scope="row"><strong>roleinfo</strong></th><td>Gets info about a role.</td><td>rinfo</td><td>0</td><td>《roleinfo|rinfo》 <role></td></tr>
<tr><th scope="row"><strong>serverinfo</strong></th><td>Gets info about the current server.</td><td>si, sinfo</td><td>0</td><td>r.《serverinfo|si|sinfo》</td></tr>
<tr><th scope="row"><strong>tag</strong></th><td>Allows you to do stuff with tags</td><td>tagcmd, bottag</td><td>0</td><td>r.《tag|tagcmd|bottag》 <add|create|all|edit|delete|get|name:string> [args]</td></tr>
<tr><th scope="row"><strong>userinfo</strong></th><td>Gets info about you or another user.</td><td>ui, useri</td><td>0</td><td>r.《userinfo|ui|useri》 [member]</td></tr>
<table>

<h2 id="jumpLinkIdiotic">Idiotic Commands</h2>
<table>
<tr><th scope="col">Command</th><th scope="col">Description</th><th scope="col">Aliases</th><th scope="col">Permission Level</th><th scope="col">Usage</th>
<tr>
<tr><th scope="row"><strong>achievement</strong></th><td>Generate an achievement.</td><td></td><td>0</td><td>r.achievement <text></td></tr>
<tr><th scope="row"><strong>beautiful</strong></th><td>Makes you or someone else beautiful</td><td></td><td>0</td><td>r.beautiful [member]</td></tr>
<tr><th scope="row"><strong>blame</strong></th><td>Blame something. wow rood</td><td></td><td>0</td><td>r.blame <text></td></tr>
<tr><th scope="row"><strong>bobross</strong></th><td>Gives you or someone a bobross makeover.</td><td></td><td>0</td><td>r.bobross [member]</td></tr>
 <tr><th scope="row"><strong>brighten</strong></th><td>Brightens a user or yourself by 50%</td><td></td><td>0</td><td>r.brighten [member]</td></tr>
 <tr><th scope="row"><strong>challenger</strong></th><td>You or someone else can become the challenger.</td><td></td><td>0</td><td>r.challenger [member]</td></tr>
 <tr><th scope="row"><strong>confused</strong></th><td>Are you confused?</td><td></td><td>0</td><td>r.confused [member]</td></tr>
 <tr><th scope="row"><strong>crush</strong></th><td>Do you have a crush on someone?</td><td></td><td>0</td><td>r.crush [member]</td></tr>
 <tr><th scope="row"><strong>darken</strong></th><td>Darkens a user or yourself by 50%</td><td></td><td>0</td><td>r.darken [member]</td></tr>
 <tr><th scope="row"><strong>greyscale</strong></th><td>Greyscales a user or yourself.</td><td></td><td>0</td><td>r.greyscale [member]</td></tr>
 <tr><th scope="row"><strong>invert</strong></th><td>Inverts a user or yourself.</td><td></td><td>0</td><td>r.invert [member]</td></tr>
 <tr><th scope="row"><strong>sepia</strong></th><td>Gives someone or yourself a tinge of red.</td><td></td><td>0</td><td>r.sepia [member]</td></tr>
 <tr><th scope="row"><strong>slap</strong></th><td>Slaps a user *ouch*.</td><td></td><td>0</td><td>r.slap <member></td></tr>
</table>