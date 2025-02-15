# Server Codes
This document is available in the following languages: PLACEHOLDER

Pineapple offers a server code tracker for the online game [florr.io](https://florr.io) which can be useful when hunting Super mobs or finding servers to farm in. The following offers a overview of its functions.

## Servers Tracker
The primary server tracking function can be accessed with `.servers`, or `.sv` for short. The command syntax is `.servers (map)`. There are a few shortcuts for the different maps, outlined below:
```
g → Garden
d → Desert
o → Ocean
j → Jungle
ah → Ant Hell
h → Hel
sw → Sewers
bg → Battle Ground
all → All Servers
```
This function returns the server codes of all servers if no argument is passed, or `all` is specified.

Server codes are given with their `cp6.forceServerID` command prefilled and with a copy button at the 

### Server Warnings
Pineapple also tracks certain attributes of servers and annotates the `cp6.forceServerID` command to include them as needed.

#### Crashed
Servers that have crashed are annotated with a `// CRASHED` tag. This means that the server that the build is on has unexpectedly crashed and is a very rare scenario.

#### Reverted
Servers that are annotated with a `// REVERTED` tag are on a game version that has been reverted to an older game version. This usually occurs when M28 pushes a build that has a critical bug, prompting a game revert. These servers are essentially `OLD` servers but with a newer version rather than an old server. It is possible to force yourself into these reverted servers.

### Old
Old servers are annotated with a `// OLD` tag, which means that they are on a game version that is older than the most current version. This can be especially helpful in the case that a Super mob spawns in an old server because it is possible to force yourself into an old server.

In order to force yourself into an old server, you will need the `cp6.forceServerID` command.