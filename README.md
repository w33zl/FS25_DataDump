# Data Dump for Farming Simulator (FS22_DataDump)

![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/w33zl/FS22_DataDump/total)


The main purpose of this mod is to save the global tables, functions, classes and variables from Farming Simulator to files. Use these files to better understand the Farming Simulator object model through reverse engineering.

![Global functions, tables, classes and variables](WZLModding_DataDump_GlobalTables.PNG)

With these global objects as a starting point, you can then use the console command 'dtSaveTable' from the mod 'PowerTools: Developer' to write whole Lua tables (and full table hierarchies) to file for further analysis.

E.g. if the output of Data Dump contains a global table called 'g_gui' you can then execute the console command 'dtSaveTable g_gui g_gui.lua 10' to save the g_gui table to a file called g_gui.lua with a max dept of 10 levels.

## USAGE
1. Open the developer console in FS. 
2. Type 'ddDump' and hit [ENTER]
3. Review the files in the '..\Documents\My Games\FarmingSimulator2022\modSettings\FS22_000_DataDump' folder

![alt text](WZLModding_DataDump_Console.PNG)




## Download my mods
To download my mods, please visit my FS19 or FS22 page on the official Giants ModHub page:

[![My FS22 Mods](https://github.com/w33zl/w33zl/raw/main/GitHubIcons_MH_FS19.png)](https://www.farming-simulator.com/mods.php?title=fs2019&filter=org&org_id=140742)
[![My FS22 Mods](https://github.com/w33zl/w33zl/raw/main/GitHubIcons_MH_FS22.png)](https://www.farming-simulator.com/mods.php?title=fs2022&filter=org&org_id=140742)
[![My FS25 Mods](https://github.com/w33zl/w33zl/raw/main/GitHubIcons_MH_FS25.png)](FS25.md)


## Open Modding Alliance
I'm a contributor and co-founder of the [Open Modding Alliance](https://github.com/open-modding-alliance) (OMA). The core of OMA is collaboration and knowledge sharing for the greater good of the Farming Simulator community. If you are a modder or create assets for FS I can recommend paying this page a visit:

[![Open Modding Alliance](https://github.com/w33zl/w33zl/raw/main/GitHubIcons_OMA.png)](https://github.com/open-modding-alliance)


## Connect with me
📫 Want to get in touch? If you have bugs to report or want to suggest improvements, it is easiest to send a ticket here on GitHub. Otherwise you can find me on Facebook, Patreon and Discord:


[![WZL Modding on Facebook](https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/facebook/default.svg)](https://fb.com/w33zl) *&nbsp;* [![WZL Modding on Patreon](https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/patreon/default.svg)](https://www.patreon.com/wzlmodding) *&nbsp;* [![https://discordapp.com/users/w33zl](https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg)](https://discordapp.com/users/w33zl)


## Like the work I do?
I love to hear you feedback so please check out my [Facebook](https://www.facebook.com/w33zl). If you want to support me you can become my [Patron](https://www.patreon.com/wzlmodding) or buy me a [Ko-fi](https://ko-fi.com/w33zl) :heart:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/X8X0BB65P) [![Support me on Patreon](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Dwzlmodding%3F%26type%3Dpatrons&style=for-the-badge)](https://patreon.com/wzlmodding?)

