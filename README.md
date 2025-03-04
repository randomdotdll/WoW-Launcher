# WoW-Launcher
A game launcher for World of Warcraft that allows you to connect to custom servers.

[![Support](https://img.shields.io/badge/discord-join-7289DA.svg)](https://arctium.io/discord)

### License & Copyright

The WoW Launcher source is licensed under the [MIT](https://github.com/Arctium/WoW-Launcher/blob/master/LICENSE) license.

### Binary Releases
You can find signed binary releases at [Arctium](https://arctium.io/wow)

### Supported Game Versions (Windows x86 64 bit)
* Retail: 9.1.0 (default)
* Classic: 2.5.2 (--version Classic)
* Classic Era: 1.14.0 (--version ClassicEra)

### Supported Game Versions (Windows ARM 64 bit)
* Retail: Coming Soon
* Classic: Coming Soon
* Classic Era: Coming Soon

## Building

### Build Prerequisites
* [.NET Core SDK 6.0.0-rc.2 or later](https://dotnet.microsoft.com/download/dotnet/6.0)
* Optional for native builds: C++ workload through Visual Studio 2022 or latest C++ build tools

### Build Instructions Windows (native)
* Execute `dotnet publish -r win-x64 /p:Configuration=Release /p:platform="x64" --self-contained`
* Native output is placed in `build\Release\bin\native`

### Usage Windows
1. Copy `Actium WoW Launcher.exe` to your World of Warcraft folder.
2. Optional: Edit the `WTF/Config.wtf` to set your portal or use a different config file with the `-config Config2.wtf` launch arg.
3. Run the `Actium WoW Launcher.exe`

### Parameters
* Use --help

## WARNING

DO NOT USE THIS AS BASE FOR ANY OFFICIAL SERVER TOOLS.
IT WILL GET YOU BANNED THERE!!!

## Special Request <3

Please do NOT remove the name `arctium` from the final binary.
Blizzard filters their crash logs based on localhost and the string `arctium` in the binary name. 
