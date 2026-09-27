# KR Replay Studio — Windows downloads

[**Download KRReplayStudio.exe**](https://github.com/qCiels/kr-replay-studio-downloads/releases/latest/download/KRReplayStudio.exe)

Download the executable, save it in a permanent folder, and double-click it to open the home page. Windows 10/11 x64; no separate Python installation is needed. This is an unsigned build.

Live data connects automatically. No invitation, account, or personal Riot API key is required. The administrator's Riot API key stays on the hosted backend, rather than in the executable. The free backend can take about a minute to wake after inactivity.

## Enhancements maintained by qCiels

This project builds on [AGaaloul/league-replay-library](https://github.com/AGaaloul/league-replay-library). The original project belongs to its original authors; this page highlights the desktop and service improvements maintained in qCiels' version.

- A standalone Windows executable that opens directly to the desktop GUI.
- Automatic backend access with server-issued tokens and locally encrypted token storage.
- KR Challenger rankings with player match-history navigation and available replay downloads.
- Ladder and player-name caching, background preloading, and retry handling for failed name lookups.
- A Champions search that starts empty and filters current KR Challenger players by champion and minimum seasonal games.
- LCK player account selection and clearer dark-themed selection controls.
- A local saved-replay library and playback through a compatible installed League client.

## Replay availability

Only available replays can be downloaded. Playback requires League of Legends installed with a compatible patch; old replays do not become permanently playable. Live features depend on the hosted service and upstream data availability.

App data is stored in `%LOCALAPPDATA%\KRReplayLibrary`. Replacing the EXE keeps your saved data.

## About this repository

This public repository hosts executable downloads and release notes. Application source is maintained separately in a private repository. GitHub's automatically generated source archives here contain this download page, not the application source.

KR Replay Studio isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games and associated properties are trademarks or registered trademarks of Riot Games, Inc.
