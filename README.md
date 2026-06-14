# madout-dlls
Repository of modified and original Dynamic Link Libraries for the game MadOut2 BigCityOnline for PC/Windows. 

# What is this for?
Access pre-modified and original versions of DLLs for the game. This will allow you to make pull requests and easily use GameAssembly DLLs, potentially others.

# How to use?
DLLs labeled without a long manifest ID at the start of the parenthetical are for the latest release of the game, 2 July 2019. Others have their manifest ID in the parenthetical. Move the original `Assembly-CSharp.dll` out of `game_data/managed/` and replace it with your `Assembly-CSharp.dll` of choice. Make sure that it is named `Assembly-CSharp.dll`. Your game version has to match that of the DLL - in most cases, you will never have to worry about this, however you have to use the exact manifest ID listed in the parenthetical if there is one - or else the game will crash. If you don't know how to or are not willing to research how to open the Steam console or use SteamDB to download the appropriate manifest, please stick to the latest version. Some files were withheld for copyright reasons, and you can find such files [here](https://discord.gg/RNybwF2ES5). 

# How to verify source code, mods, etc?
You can use a program called DNSpy in order to read through the code of the DLLs, ensuring that there is nothing malicious hiddden there. Additionally, some .reg files shared on the Discord server can also be verified with a hex editor. It touches nothing outside of the settings directory for the game itself. 

# What should I do, should I modify a DLL?
Please make a pull request where we can verify that you have not put malware or dangerous vulnerabilities/backdoors into the file. We can and will do so. This includes any sort of mechanism that would allow it to replace executable files or load code from any server, regardless of what that server is or what it has on it.

# Credits
zetsense on GitHub for the original MadOut2Restore for 2019 version, which brought offline support to that version. I have modified many other things. All contributors to the repo.
