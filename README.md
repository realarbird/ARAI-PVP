# ARAI-PVP
AR AI PVP mod for Minecraft Java!


Download: https://modrinth.com/mod/arai-pvp


ARAIpvp:

ARAIpvp is a Fabric mod for Minecraft Java 26.1.x. It adds ARAIpvp, a player-like PvP training bot that uses fast local combat logic with optional OpenRouter free-model tactic updates.


Requirements:

Minecraft Java 26.1.x

Fabric Loader 0.19.2+

Fabric API 0.147.0+26.1.2 or compatible 26.1.x release

Java 25

The Gradle build uses toolchains and can provision Java 25 locally.


Commands:

/araipvp spawn <easy|normal|hard|expert|nightmare> <single|loop> [model] starts a duel.

/araipvp end stops the current duel or practice loop.

/araipvp openrouter key set <key> saves an OpenRouter API key.

/araipvp openrouter key clear removes the saved key.

/araipvp openrouter key status checks whether a key is configured.

/araipvp openrouter models refresh fetches current free model IDs.

/araipvp openrouter models list prints loaded free model IDs.

/araipvp openrouter models set <modelId> sets the default model for commands.


The default OpenRouter model is google/gemma-4-31b-it:free. The environment variable OPENROUTER_API_KEY is also supported and takes priority over the saved config key. If the key is missing when a player tries to start or open ARAIpvp, the mod shows a clickable prompt for the free key page: 
https://openrouter.ai/workspaces/default/keys.

