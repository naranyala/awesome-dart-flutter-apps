# Awesome Dart & Flutter Apps

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](LICENSE)
[![Last reviewed](https://img.shields.io/badge/last%20reviewed-2026--09--27-blue.svg)](#contributing)

A curated catalog of **real, open-source applications built with Dart and Flutter** — the apps you can
actually install and use, not tutorials, not starter templates, not package registries.

Focused on software **hosted on GitHub or Codeberg**, because that is where a self-hostable,
auditable, forkable app can actually live. Links to other forges are welcome (see
[Contributing](#contributing)).

**Every repository URL in this list was checked to resolve on 2026-09-27.** Most were also verified
to contain a `pubspec.yaml` in their git tree, so they are genuinely Dart/Flutter projects and not
JavaScript, Kotlin or Electron apps wearing a Flutter label.

---

## Contents

- [Highlights](#highlights)
- [Chat & Messaging](#chat--messaging)
- [Social & Fediverse](#social--fediverse)
- [Forums & Communities](#forums--communities)
- [Media](#media)
  - [Video Players](#video-players)
  - [Music Players](#music-players)
  - [Podcasts & Audiobooks](#podcasts--audiobooks)
  - [IPTV & Live TV](#iptv--live-tv)
  - [E-books, Comics & Manga](#e-books-comics--manga)
  - [Photos & Images](#photos--images)
  - [Download Managers](#download-managers)
  - [Subtitles](#subtitles)
- [Productivity](#productivity)
  - [Notes, Markdown & PKM](#notes-markdown--pkm)
  - [Tasks & To-Do](#tasks--to-do)
  - [Habits, Focus & Time Tracking](#habits-focus--time-tracking)
  - [Calendars & Meal Planning](#calendars--meal-planning)
- [System & Utilities](#system--utilities)
  - [File Transfer & File Managers](#file-transfer--file-managers)
  - [Launchers & Keyboards](#launchers--keyboards)
  - [Network, VPN & Proxy](#network-vpn--proxy)
  - [System Monitoring & Server Admin](#system-monitoring--server-admin)
  - [Passwords, 2FA & Identity](#passwords-2fa--identity)
  - [Clipboard](#clipboard)
  - [Translation](#translation)
  - [RSS, News & Weather](#rss-news--weather)
  - [Remote Access & Bridges](#remote-access--bridges)
- [Developer Tools & Infrastructure](#developer-tools--infrastructure)
- [Finance](#finance)
  - [Budgeting & Accounting](#budgeting--accounting)
  - [Invoicing, POS & Trading](#invoicing-pos--trading)
  - [Crypto Wallets](#crypto-wallets)
- [Health, Fitness & Mental Health](#health-fitness--mental-health)
- [Education & Learning](#education--learning)
- [E-Commerce, Food & Storefronts](#e-commerce-food--storefronts)
- [Maps, Transit & Field Data](#maps-transit--field-data)
  - [OpenStreetMap & Field Data](#openstreetmap--field-data)
  - [Navigation & Routing](#navigation--routing)
  - [Outdoor & GPS Tracking](#outdoor--gps-tracking)
  - [Marine & Boating](#marine--boating)
  - [Public Transit](#public-transit)
  - [Weather & Radar](#weather--radar)
  - [Aviation](#aviation)
  - [Map Engines & Toolkits](#map-engines--toolkits)
- [Games](#games)
  - [Board & Card Games](#board--card-games)
  - [Arcade, Puzzle & Action](#arcade-puzzle--action)
  - [Roguelikes & Strategy](#roguelikes--strategy)
  - [Game Engines & Toolkits](#game-engines--toolkits)
- [Plain Dart (non-Flutter)](#plain-dart-non-flutter)
- [Notable but Unmaintained](#notable-but-unmaintained)
- [Related Lists & Directories](#related-lists--directories)
- [Contributing](#contributing)

---

## Highlights

If you only install a handful of open-source apps from this list, these are the ones worth your time.

| App | What it is | Why it's here |
|---|---|---|
| [Spotube](https://github.com/team-spotube/spotube) | Spotify-compatible client | The single most popular Flutter app in the world by stars; works without a Premium account |
| [FluffyChat](https://github.com/krille-chan/fluffychat) | Matrix client | The reference implementation for "serious, secure, cross-platform Flutter messaging" |
| [Gopeed](https://github.com/GopeedLab/gopeed) | Download manager | Flutter UI over a Go core, with a browser extension and REST API |
| [Hiddify](https://github.com/hiddify/hiddify-app) | Proxy/VPN client | 30k+ stars, ships on every platform, wraps sing-box/Xray |
| [MusicPod](https://github.com/ubuntu-flutter-community/musicpod) | Music/radio/podcast player | A mature, genuinely pleasant desktop app from the Ubuntu community |
| [LocalSend](https://github.com/localsend/localsend) | Nearby file transfer | A polished Flutter app that replaced a popular proprietary tool |
| [Cake Wallet](https://github.com/cake-tech/cake_wallet) | Monero/Bitcoin wallet | The flagship open-source Flutter crypto wallet |
| [RustDesk](https://github.com/rustdesk/rustdesk) | Remote desktop | A fully open-source TeamViewer alternative; Flutter is the main client |
| [Medito](https://github.com/meditohq/medito-app) | Meditation | Permanently free, ad-free, foundation-run |
| [Lichess Mobile](https://github.com/lichess-org/mobile) | Chess | The largest and most production-grade Flutter app in existence |
| [Plezy](https://github.com/edde746/plezy) | Plex/Jellyfin/Emby client | The best-looking modern media client for TV and desktop |
| [Aves](https://github.com/deckerst/aves) | Photo gallery | Deep metadata support (motion photos, 360°, GeoTIFF) most galleries skip |
| [Flame](https://github.com/flame-engine/flame) | 2D game engine | The engine nearly every open-source Flutter game is built on |
| [wger](https://github.com/wger-project/flutter) | Workout manager | Flutter front end for a large, mature self-hosted fitness server |
| [Immich mobile](https://github.com/immich-app/immich) | Photo app | The mobile client of the fastest-growing self-hosted photo server |

---

## Chat & Messaging

- **[FluffyChat](https://github.com/krille-chan/fluffychat)** — The best-known Flutter Matrix client: end-to-end encryption, encrypted backups, spaces, cross-signing, Material You. `AGPL-3.0` · iOS, Android, Web, Linux · *active*
- **[Extera](https://github.com/ExteraApp/Extera)** — Feature-heavy FluffyChat fork for Matrix, aimed at both mobile and desktop. Mirrored to [codeberg.org/tamtan/Extera](https://codeberg.org/tamtan/Extera). `AGPL-3.0` · iOS, Android, Linux, Windows, macOS, Web · *active*
- **[Twake Chat](https://github.com/linagora/twake-on-matrix)** — Decentralized Matrix client built by Linagora, themable and feature-complete. `AGPL-3.0` · iOS, Android, Web, Linux, Windows, macOS · *active*
- **[Zulip](https://github.com/zulip/zulip-flutter)** — Flutter client for the Zulip team chat platform, maintained alongside the project. `Apache-2.0` · iOS, Android · *active*
- **[BlueBubbles](https://github.com/BlueBubblesApp/bluebubbles-app)** — Brings iMessage to Android, Windows, Linux, macOS and the web, with a full Flutter + server ecosystem. `Apache-2.0` · iOS, Android, Web, Linux, Windows, macOS · *active*
- **[Kabootar](https://github.com/royalpinto007/Kabootar)** — Offline mesh messenger that hops messages phone-to-phone over Bluetooth and Wi-Fi. No server, no SIM. `MIT` · Android, iOS · *active*
- **[Chatsen](https://github.com/chatsen/chatsen)** — Cross-platform Twitch Chat reader with third-party addon support. `AGPL-3.0` · Windows, Linux, macOS · *active*

## Social & Fediverse

- **[Aria](https://github.com/poppingmoon/aria)** — Cross-platform Misskey client for the fediverse. `AGPL-3.0` · Android, iOS, Web, Linux, Windows, macOS · *active*
- **[Squawker](https://github.com/j-fbriere/squawker)** — Open-source, privacy-oriented Twitter/X client. `MIT` · Android, iOS, Web · *active*
- **[flabr](https://github.com/iska9der/flabr)** — Habr (habr.com) reader client. `MIT` · Android, iOS, Web · *active*
- **[e1547](https://github.com/clynamic/e1547)** — A surprisingly sophisticated e621 browser. `GPL-3.0` · Android, iOS, Web · *active*
- **[talawa](https://github.com/PalisadoesFoundation/talawa)** — Community organization management: events, groups, memberships, with a Flutter app and GraphQL API. `GPL-3.0` · Android, iOS, Web · *active*
- **[Resonate](https://github.com/AOSSIE-Org/Resonate)** — "Clubhouse, but open source" — a social voice platform with a Flutter client. `GPL-3.0` · Android, iOS, Web · *active*
- **[Fritter](https://github.com/jonjomckay/fritter)** — Privacy-friendly Twitter frontend for mobile. `MIT` · Android, iOS · *slowing*

## Forums & Communities

- **[Forum App (XenForo)](https://github.com/forumcopilot/xenforoapp)** — Open-source Flutter template that turns a single XenForo community into a full app. `MIT` · Android, iOS, macOS, Web, Windows, Linux · *active*
- **[StarForum](https://github.com/cubevlmu/StarForum)** — Cross-platform Flarum forum client with local SQLite caching and a Material 3 desktop split view. `GPL-2.0` · Android, iOS, Windows, macOS, Linux · *active*
- **[flutter-nga](https://github.com/loshine/flutter-nga)** — Client for the NGA forum: boards, threads, posting, multi-account, private messages. `Apache-2.0` · Android, iOS, Web · *active*

---

## Media

### Video Players

- **[Plezy](https://github.com/edde746/plezy)** — Modern Plex/Jellyfin/Emby client for desktop, mobile and TV with mpv playback, HDR/Dolby Vision, downloads and watch-party sync. `GPL-3.0` · Android, iOS, tvOS, Windows, macOS, Linux · *active*
- **[Ghosten Player](https://github.com/GhostenEditor/Ghosten-Player)** — Feature-rich player with cloud-drive direct playback, metadata scraping, IPTV, danmaku and file management. `AGPL-3.0` · Android, Android TV, macOS, Windows, Web · *active*
- **[NipaPlay-Reload](https://github.com/AimesSoft/NipaPlay-Reload)** — Local and NAS video player with danmaku rendering, multi-format subtitles and SMB/WebDAV/Jellyfin sources. `MIT` · Android, iOS, Windows, macOS, Linux · *active*
- **[Moonfin](https://github.com/Moonfin-Client/Moonfin-Core)** — Jellyfin/Emby client reaching phones, desktop, Android TV, Fire TV, Apple TV, Tizen and the web as a PWA. `GPL-2.0` · Android, iOS, tvOS, Windows, macOS, Linux, Web · *active*
- **[Jellyflix](https://github.com/jellyflix-app/jellyflix)** — Straightforward, reliable cross-platform Jellyfin client with transcoded downloads and HDR tonemapping. `GPL-3.0` · Android, iOS, Windows, macOS, Linux, Web · *active*
- **[Debrify](https://github.com/varunsalian/debrify)** — "Personal media hub" client for streaming and organizing media from your own services. `AGPL-3.0` · Android, Android TV, iOS, Windows, macOS, Linux, Web · *active*
- **[Fathom](https://github.com/Fathom-Media/fathom)** — All-in-one Jellyfin client with a built-in YouTube player and Seerr integration. `AGPL-3.0` · Android, Android TV, iOS, Windows, macOS, Linux, Web · *active*
- **[Dacx](https://github.com/BurntToasters/Dacx)** — Fast desktop music/video player built on Flutter + libmpv, with an equalizer. `GPL-3.0` · Windows, macOS, Linux · *active*
- **[SportStream](https://codeberg.org/tg-macos/sport_stream)** — Live sports streaming for phone and Android TV with libmpv, stream auto-fallback and ad blocking. **Codeberg** · Android, Android TV, Web · *active*
- **[TVNinja](https://github.com/Giuig/tvninja)** — M3U8/Xtream IPTV player with a persistent mini-player and auto picture-in-picture. `GPL-3.0` · Android, Web · *active*

### Music Players

- **[Spotube](https://github.com/team-spotube/spotube)** — Plugin-powered Spotify-compatible client that needs no Premium account; downloads tagged audio and plays it locally via mpv. Also mirrored at [codeberg.org/KRTirtho/spotube](https://codeberg.org/KRTirtho/spotube). `BSD-4-Clause` · Windows, macOS, Linux, Android, iOS, Web · *very active*
- **[Finamp](https://github.com/finamp-app/finamp)** — Jellyfin music client with a polished Material 3 UI; one of the largest active Flutter repos. `MPL-2.0` · Android, iOS · *very active*
- **[MusicPod](https://github.com/ubuntu-flutter-community/musicpod)** — Music, radio, TV and podcast player from the Ubuntu community. `GPL-3.0` · Linux, Windows, macOS, Android · *very active*
- **[JellyBox](https://github.com/avdept/JellyBoxPlayer)** — Native Jellyfin/Emby/Navidrome music player with a Spotify-like UI, CarPlay and Android Auto. `AGPL-3.0` · Android, iOS, Windows, macOS, Linux · *active*
- **[Harmonoid](https://github.com/harmonoid/harmonoid)** — Local music library player with playlists, synced lyrics, pitch shift and volume boost. *(non-standard license)* · Windows, Linux, macOS, Android, iOS · *active*
- **[Sylvakru](https://github.com/AfalpHy/sylvakru)** — Cross-platform player for local libraries and self-hosted services (Navidrome, Emby, WebDAV). `Apache-2.0` · Android, iOS, Windows, macOS, Linux · *active*
- **[Echo MPD](https://github.com/rd6260/echo_mpd)** — Modern mobile client for Music Player Daemon. `MIT` · Android, iOS · *active*
- **[Koel Player](https://github.com/koel/player)** — Official mobile app for the Koel music server. *(no license file in repo — verify)* · Android, iOS · *active*
- **[Pure Music](https://github.com/qingyueyin/Pure-music)** — Local music player built specifically for Windows. `GPL-3.0` · Windows · *active*
- **[AntiiQ](https://github.com/coleblvck/AntiiQ)** — Local-first offline Android music player for collectors: gapless/crossfade, 15-band EQ, speed and pitch control. `GPL-3.0` · Android · *active*
- **[Linthra](https://github.com/TheZupZup/Linthra)** — Local-first music player with WebDAV support. `AGPL-3.0` · Android, Linux · *active*
- **[Vibin' App](https://codeberg.org/mickkc/vibin-app)** — Client for the self-hosted Vibin' music streaming server: albums, artists, playlists, lyrics. **Codeberg** · Android, iOS, Windows, macOS, Linux, Web · *active*
- **[OwnTone Sync](https://codeberg.org/Edu_Coder/owntone-sync)** — Syncs your collection from a self-hosted OwnTone server for offline listening, with scrobble write-back. **Codeberg** · Android · *active*
- **[Namida](https://github.com/namidaco/namida)** — Music and video player with YouTube streaming, downloads, SponsorBlock and Subsonic/WebDAV support. ⚠️ *source-available, not OSI-approved* · Android · *active*

### Podcasts & Audiobooks

- **[Tsacdop](https://github.com/tsacdop/tsacdop)** — Simple, friendly podcast player with group management, OPML import/export, sleep timer, skip-silence and volume boost. `GPL-3.0` · Android, Windows, macOS, Linux, Web · *very active*
- **[PinePods](https://github.com/madeofpendletonwool/PinePods)** — Self-hosted podcast server in Rust with an official Flutter mobile client, offline downloads, Android Auto, CarPlay and gpodder-compatible sync. `GPL-3.0` · Android, iOS (+ web/desktop) · *very active*
- **[Storii](https://github.com/likhithpraveenk/storii)** — Feature-rich Audiobookshelf client: offline download manager, sleep timer, bookmarks, multi-server/OIDC, Android Auto. `GPL-3.0` · Android, iOS · *active*
- **[yaabsa](https://github.com/Vito0912/yaabsa)** — Unofficial, responsive Audiobookshelf client. `AGPL-3.0` · Android, iOS, Web · *active*
- **[Anytime Podcast Player](https://github.com/amugofjava/anytime_podcast_player)** — Straightforward podcast player written in Flutter. `BSD-3-Clause` · Android, iOS · *active*
- **[Audix](https://github.com/JinBlack/audix)** — Audiobook player for local `.m4b` + `.cue` libraries with background playback, chapter navigation and sleep timer. *(no license file)* · Android, iOS, Web · *new*

### IPTV & Live TV

> IPTV players are popular but the ecosystem is full of apps built for circumventing access controls. Everything listed here is a general-purpose player or client for content you are entitled to watch.

- **[clubTivi](https://github.com/clubanderson/clubTivi)** — IPTV player with multi-provider aggregation, 4-tier EPG auto-matching and automatic stream failover. `Apache-2.0` · Android, Android TV, Windows, macOS, Linux · *active*
- **[HTV](https://github.com/HTWMedia/HTV)** — Free, ad-free network live-TV app for phones and Android TV boxes. `Apache-2.0` · Android, Android TV · *active*
- **[Tiwee](https://github.com/neffex97/Tiwee)** — IPTV player for global live TV with country and category filtering. `GPL-3.0` · Android, Android TV, iOS · *active*
- **[XPlayer](https://github.com/TNT-Likely/xplayer)** — Cross-platform IPTV/M3U player with grouping, search and the iptv-org playlist built in. `MIT` · Android, Android TV, iOS, iPadOS, macOS, Windows, Linux · *active*
- **[sky-tv](https://github.com/sky22333/sky-tv)** — Video player shell where you import your own live and on-demand sources. `GPL-3.0` · Android, iOS, Windows, macOS, Linux · *active*
- **[ipdigi](https://github.com/atillayurtseven/ipdigi-oss)** — Netflix-style Xtream/M3U player with TMDB enrichment, EPG, watchlists and mpv playback. `GPL-3.0` · Android, Android TV, iOS, macOS, Windows, Linux · *active*
- **[pusoo](https://github.com/iamutaki/pusoo)** — IPTV player with HLS/DASH/MP4/MKV, external subtitle search, ClearKey/Widevine DRM and source fallback. `GPL-3.0` · Android · *active*
- **[iptvs](https://github.com/GCHOfficial/iptvs)** — Stalker/Xtream/M3U player with true HDR (D3D11 on Windows, libplacebo on Linux). `GPL-3.0` · Windows, Android, Android TV, Linux · *new*
- **[Lotus IPTV](https://github.com/ylmyg/FlutterIPTV)** — IPTV player with M3U auto-grouping, local logos and hardware-accelerated playback. `MIT` · Windows, Android, Android TV · *active*
- **[Universal TV](https://github.com/frederikstonge/universal_tv)** — Multi-provider IPTV client with M3U pagination tokens, XMLTV EPG and casting. *(no license file)* · cross-platform · *active*
- **[Ammonite](https://codeberg.org/Arunhegde1231/ammonite)** — Cross-platform PeerTube client. **Codeberg** · Android, iOS, desktop · *last updated 2024*

### E-books, Comics & Manga

- **[Mangayomi](https://github.com/kodjodevf/mangayomi)** — Tachiyomi-style reader for manga, webtoons, novels, anime and movies with tracker sync and backups. `Apache-2.0` · Android, iOS, macOS, Linux, Windows · *active*
- **[VeneraNext](https://github.com/CyrilPeng/Venera-Next)** — Cross-platform manga reader with local libraries (CBZ/ZIP/7z/PDF/EPUB), WebDAV libraries and a JS extension API. `GPL-3.0` · Android, iOS, Windows, macOS, Linux · *active*
- **[Mangatan](https://github.com/1Selxo/Mangatan)** — Mangayomi fork focused on Yomitan-style dictionary lookup, OCR overlays and subtitle mining. `GPL-3.0` · Android, iOS, Windows, macOS, Linux, Web · *active*
- **[Jidoujisho](https://github.com/arianneorpilla/jidoujisho)** — Immersion language-learning suite with manga/webtoon support, dictionaries and SRS. `GPL-3.0` · Android, iOS · *active*
- **[Tachidesk-Sorayomi](https://github.com/Suwayomi/Tachidesk-Sorayomi)** — Manga reader that reads from a self-hosted Tachidesk/Suwayomi server. `MPL-2.0` · Android, iOS · *slowing*
- **[Flutter Manga Reader](https://github.com/TesteurManiak/flutter_manga_reader)** — Tachiyomi/Mihon-alike with Tachiyomi backup import and offline chapter downloads. `Apache-2.0` · Android, iOS, desktop, Web · *active*
- **[Hikari](https://github.com/OnoPUNPUN/Hikari)** — MangaDex-based reader with classic page-turn and webtoon vertical modes. `MIT` · Android, iOS, Web · *active*
- **[Lumina](https://github.com/MilkFeng/lumina)** — Lightweight cross-platform EPUB reader with progress sync. `MIT` · Android, iOS · *active*
- **[Yomu](https://github.com/daveragos/yomu)** — All-in-one companion for EPUB, PDF and audiobooks with progress tracking and gamified stats. `MIT` · Android, iOS · *active*
- **[LuminaBook](https://github.com/hwanjongyu/LuminaBook)** — Desktop-first EPUB library manager with a physical-bookshelf UI, reading analytics and folder monitoring. `MIT` · Windows, macOS, Linux · *new*
- **[Everbound](https://github.com/Neighborhood-Nerd/everbound-ereader-app)** — Immersive EPUB reader built on foliate-js with highlights, annotations and layout customization. `AGPL-3.0` · Android, iOS · *active*

### Photos & Images

- **[Aves](https://github.com/deckerst/aves)** — Gallery and metadata explorer: motion photos, panoramas, 360° video, GeoTIFF, SVG, XMP/EXIF browsing, map view and vault. `BSD-3-Clause` · Android, Android TV · *active*
- **[Immich mobile](https://github.com/immich-app/immich)** — Flutter mobile client for the self-hosted Immich photo and video server. `AGPL-3.0` · Android, iOS · *very active*
- **[Ente Photos](https://github.com/ente/ente)** — End-to-end encrypted Google Photos alternative with face detection, semantic search and private sharing. `AGPL-3.0` · Android, iOS · *very active*

### Download Managers

- **[Gopeed](https://github.com/GopeedLab/gopeed)** — Fast cross-platform download manager (HTTP, BitTorrent, Magnet, ed2k) with a native Flutter UI over a Go core, browser extension, REST API and JS extensions. `GPL-3.0` · Windows, macOS, Linux, Android, iOS, Web · *very active*
- **[Nadeko~don](https://github.com/izaz4141/nadekodon-rs)** — Download manager with a Rust backend and a Material 3 Flutter frontend. *(no license file)* · Linux, Windows, Android · *new*

### Subtitles

- **[Subtitle Studio](https://github.com/Msoneofficial/SubtitleStudio)** — Cross-platform subtitle editor with frame-accurate timing, video sync, regex search/replace, batch ops and multi-format export. `GPL-3.0` · Android, iOS, Windows, macOS, Linux, Web · *new*

---

## Productivity

### Notes, Markdown & PKM

- **[Butterfly](https://github.com/LinwoodDev/Butterfly)** — Powerful, minimalistic cross-platform Markdown notes with bidirectional links, canvas and graph views. `AGPL-3.0` · Android, iOS, Windows, macOS, Linux, Web · *active*
- **[Memex](https://github.com/memex-lab/memex)** — "Second brain" knowledge management for collecting documents, images and web clippings, with semantic search. `GPL-3.0` · Android, iOS, Web · *active*
- **[Better Keep](https://github.com/foxbiz/better-keep)** — Google Keep-style card notes with rich text, PIN-locked notes, end-to-end encrypted sync and audio note transcription. *(custom license)* · Android, iOS, Windows, macOS, Linux, Web · *active*
- **[Kardi Notes](https://github.com/rikodot/kardi_notes_app)** — Cross-platform encrypted note-taking with device-to-device sync. `GPL-3.0` · Android, iOS, Windows, macOS, Linux · *slowing*
- **[NexaNote](https://codeberg.org/TheZupZup/NexaNote)** — Self-hostable note app storing plain Markdown files, with stylus ink capture, notebooks and WebDAV sync. **Codeberg** *(Flutter client in `app/`)* · Linux, Android (planned) · *active*
- **[ZariNotes](https://codeberg.org/ItsZariep/ZariNotes)** — Simple multi-tabbed personal notes app with workspaces. **Codeberg** · Android · *active*
- **[Mia](https://codeberg.org/adivius/mia-app)** — Material You Android client combining notes, to-do lists and events against a self-hosted Mia server. **Codeberg** *(Flutter project in `src/`)* · Android · *active*
- **[Flutter Markdown Editor](https://github.com/adeeteya/fluttermarkdowneditor)** — Material 3 Markdown editor with live preview for mobile. `MIT` · Android, iOS · *active*
- **[Memo](https://github.com/olmps/memo)** — Programming-oriented open-source spaced-repetition flashcard app. `BSD-3-Clause` · Android, iOS, Windows, macOS, Linux · *slowing*

### Tasks & To-Do

- **[ntodotxt](https://github.com/tmaegel/ntodotxt)** — Manages your `todo.txt` file locally or over WebDAV (e.g. Nextcloud). `MIT` · Android, iOS · *active*
- **[Everyday Tasks](https://github.com/jenspfahl/everydaytasks)** — Track, log and schedule recurring everyday tasks. `GPL-3.0` · Android, iOS · *active*
- **[Zest](https://github.com/darkmoonight/Zest)** — Material You task manager with categories, subtasks, tags, a 365-day heatmap and actionable notifications. `MIT` · Android · *active*
- **[Purple Task](https://github.com/mivoligo/purple_task)** — Simple cross-platform to-do app with multiple lists. `MIT` · Android, iOS, Windows, macOS, Linux · *slowing*
- **[Taskwarrior (Flutter)](https://github.com/CCExtractor/taskwarrior-flutter)** — Taskwarrior rebuilt in Dart, shipping both a GUI and a terminal client. `GPL-3.0` · Android, CLI · *active*

### Habits, Focus & Time Tracking

- **[Time Cop](https://github.com/hamaluik/timecop)** — Privacy-first automatic time tracking with project and activity timelines. `Apache-2.0` · Android, iOS · *active*
- **[Table Habit](https://github.com/friesi23/mhabit)** — "Micro habits" tracker with charts and light-touch daily logging. `Apache-2.0` · Android · *active*
- **[Habo](https://github.com/xpavle00/Habo)** — Habit tracker with detailed statistics and streaks. `GPL-3.0` · Android · *active*
- **[Norm](https://github.com/tusharonly/norm)** — Minimal habit tracker focused on fast daily logging. `GPL-3.0` · Android · *slowing*
- **[Break.Down.Timer](https://github.com/jenspfahl/bdt)** — Pomodoro-style timer that fires configurable break notifications while running. `MIT` · Android · *active*

### Calendars & Meal Planning

- **[KitchenOwl](https://github.com/TomBursch/kitchenowl)** — Self-hosted shopping list, recipe and meal planner with real-time multi-user sync (Flask backend + Flutter frontend). Mirrored at [codeberg.org/tombursch/kitchenowl](https://codeberg.org/tombursch/kitchenowl) *(Flutter client in `kitchenowl/`)*. `AGPL-3.0` · Android, iOS, Web, Linux, macOS, Windows · *very active*
- **[SeasonCalendar](https://github.com/seasoncalendar/seasoncalendar)** — Calendar specialised for tracking seasons, holidays and recurring date events. `GPL-3.0` · Android, iOS · *slowing*

---

## System & Utilities

### File Transfer & File Managers

- **[LocalSend](https://github.com/localsend/localsend)** — Send photos and files to nearby devices over a local network, no internet required. `Apache-2.0` · Android, iOS, Web, Linux, macOS, Windows · *very active*
- **[AirDash](https://github.com/simonbengtsson/airdash)** — Cross-platform AirDrop-style photo and file transfer to nearby devices. `MIT` · Android, iOS, Windows, macOS · *active*
- **[NFile](https://github.com/Senzme/NFile)** — Glassmorphic Android file manager with native media indexing, inline players and a built-in text editor. `GPL-3.0` · Android · *active*
- **[outbag](https://codeberg.org/outbag/app)** — Official Flutter client for the outbag self-hosted file-sharing service. **Codeberg** *(Flutter project)* · Android, iOS, Web · *slowing*
- **[Sharik](https://github.com/marchellodev/sharik)** — Cross-platform file sharing over Wi-Fi or a mobile hotspot. `MIT` · Android, iOS, Linux, Windows, macOS · *inactive*

### Launchers & Keyboards

- **[FuseLauncher](https://github.com/nawka12/FuseLauncher)** — Customizable Android launcher with app drawer, widget management, notification badges and usage-based sorting. `MIT` · Android · *active*
- **[minimalauncher](https://github.com/0-manbir/minimalauncher)** — Minimal, distraction-free Android launcher with clock, calendar, weather and app shortcuts. `MIT` · Android · *slowing*
- **[TeleDeck](https://github.com/gsmlg-app/tele_deck)** — Android **system IME** (an actual `InputMethodService`) written in Flutter, with dual-screen support for handhelds. *(no license file)* · Android · *active*

### Network, VPN & Proxy

- **[Hiddify](https://github.com/hiddify/hiddify-app)** — Multi-platform auto-proxy client wrapping sing-box/Xray/Hysteria/TUIC/Trojan/SSH. `Hiddify Extended GPL-3.0` · Android, iOS, Windows, macOS, Linux · *very active*
- **[Vernet](https://github.com/osociety/vernet)** — Cross-platform network analyzer and monitoring tool: traffic inspection, connection tracking. `Apache-2.0` · Android, iOS, Windows, macOS, Linux · *very active*
- **[GMLG](https://github.com/gsmlg-app/gsmlg)** — Cross-platform developer toolbox: WHOIS, offline IP geolocation, Bluetooth scanner, network metrics dashboard and on-device model chat. *(no license declared)* · Android, iOS, macOS, Linux, Windows, Web · *active*
- **[flutterhole](https://github.com/sterrenb/flutterhole)** — Third-party Android client for the Pi-hole dashboard. `MIT` · Android · *slowing*

### System Monitoring & Server Admin

- **[ServerBox](https://github.com/lollipopkit/flutter_server_box)** — Server status charts and management tools on mobile. `AGPL-3.0` · Android, iOS · *very active*
- **[FlutterTop](https://github.com/deepMind1234/fluttertop)** — Unified Linux system monitor (CPU/GPU/RAM/disk/net/processes) reading `/proc` and `/sys`. `MIT` · Linux · *active*
- **[MaidKit](https://github.com/s12mcOvO/MaidKit)** — 100% SSH server manager: dashboard, SFTP browser, systemd, firewall, crontab, terminal. `AGPL-3.0` · Windows, macOS, Linux, Android, iOS · *active*
- **[bambuddy mobile](https://codeberg.org/DoYouHost/bambuddy-mobile)** — Unofficial client for the self-hosted Bambu Lab 3D-printer manager, including a Wear OS app. **Codeberg** · Android, Wear OS · *active*
- **[BendyStraw](https://codeberg.org/mm-dev/bendy-straw)** — Android app for managing and importing NewPipe databases. **Codeberg** · Android · *active*

### Passwords, 2FA & Identity

- **[AuthPass](https://github.com/authpass/authpass)** — KeePass 2.x (kdbx 3.x) compatible password manager for all platforms. `GPL-3.0` · Android, iOS, Windows, macOS, Linux · *active*
- **[Passy](https://github.com/glitterware/passy)** — Offline password manager with cross-platform sync. `GPL-3.0` · Android, iOS, Windows, macOS, Linux · *active*
- **[YubiOATH](https://github.com/yubico/yubioath-flutter)** — Official YubiKey OTP manager, rewritten in Flutter for desktop and Android. `Apache-2.0` · Android, Windows, macOS, Linux · *active*
- **[Ente Auth](https://github.com/ente/ente)** *(in `mobile/apps/auth`)* — Encrypted end-to-end TOTP authenticator, self-hostable. `AGPL-3.0` · Android, iOS · *active*
- **[Keyoxide](https://codeberg.org/berker/keyoxide-flutter)** — Self-sovereign digital identity and credential manager built on the Keyoxide model. **Codeberg** · Android, iOS · *active*
- **[Yivi](https://github.com/privacybydesign/irmamobile)** — Privacy-by-design IR/contactless exchange app that also handles auth flows. `GPL-3.0` · Android, iOS · *active*

### Clipboard

- **[CopyCat Clipboard](https://github.com/raj457036/copycat_clipboard)** — Cross-device clipboard manager with history, search and real-time sync between desktop and mobile. *(custom "Copycat" license)* · Android, iOS, Windows, macOS, Linux · *active*
- **[cmdclip](https://github.com/M5Devs/cmdclip)** — Offline-first clipboard **command** manager for the terminal: tag, search and re-run shell commands, with LAN sync. `GPL-3.0` · Windows, Linux, Android · *active*

### Translation

- **[Beyond Translate](https://github.com/beyondtranslate/beyondtranslate-ce)** — Translation and dictionary app with clipboard capture and "translate what you read" workflows. `AGPL-3.0` · Android, iOS · *very active*
- **[SimplyTranslate Mobile](https://github.com/manerakai/simplytranslate_mobile)** — Privacy-friendly front end for Google Translate / LibreTranslate. `GPL-3.0` · Android, iOS · *active*

### RSS, News & Weather

- **[Flux News](https://github.com/kevincfechtel/fluxnews)** — Clean, ad-free newsreader for a self-hosted miniflux backend. `BSD-3-Clause` · Android, iOS · *very active*
- **[ai-reader](https://codeberg.org/chriskaya/ai-reader)** — Self-hosted Inoreader replacement: Miniflux backend + AI ad-filter/TL;DR worker + Flutter swipe-card client. **Codeberg** *(Flutter project in `app/`)* · Android · *active*
- **[Raven](https://github.com/ksh-b/raven)** — RSS reader combining APIs and web scraping to fetch full articles. `GPL-3.0` · Android, iOS · *slowing*
- **[Glider](https://github.com/mosc/glider)** — Opinionated, ad-free Hacker News client. `MIT` · Android, iOS · *slowing*
- **[Clima](https://codeberg.org/lacerte/clima)** — Beautiful, minimal, fast weather app for GNOME and mobile. **Codeberg** · Android, iOS, Linux · *slowing*

### Remote Access & Bridges

- **[RustDesk](https://github.com/rustdesk/rustdesk)** — Open-source remote desktop / TeamViewer alternative. `AGPL-3.0` · Android, iOS, Windows, macOS, Linux · *very active*

---

## Developer Tools & Infrastructure

- **[API Dash](https://github.com/foss42/apidash)** — Cross-platform (desktop + mobile) API client for crafting requests, inspecting responses and generating integration code. `Apache-2.0` · Android, iOS, Windows, macOS, Linux · *active*
- **[kubenav](https://github.com/kubenav/kubenav)** — "The navigator for your Kubernetes clusters, in your pocket." `MIT` · Android, iOS · *active*
- **[Ubuntu Desktop Installer](https://github.com/canonical/ubuntu-desktop-installer)** — Canonical's Flutter installer for Ubuntu Desktop on Raspberry Pi. `GPL-3.0` · Linux · *slowing*
- **[quickgui](https://github.com/quickemu-project/quickgui)** — Flutter front end for `quickget`/`quickemu`, the Windows VM manager. `MIT` · Windows, Linux · *active*
- **[tldr-flutter](https://github.com/techno-disaster/tldr-flutter)** — Simplified man-pages client for tldr.sh. `MIT` · Android, CLI · *very active*
- **[mimic](https://github.com/vladimir120307-droid/mimic)** — Record a screen or drop a screenshot and get working Flutter/HTML/React code, with a Flutter desktop UI. `MIT` · CLI, Windows, macOS, Linux · *active*
- **[ADB Vision](https://github.com/sbrsubuvga/ADB)** — A typed pure-Dart ADB wrapper plus a Flutter desktop GUI: mirror, input injection, package manager, script recorder/player. *(no license file)* · Windows, macOS, Linux · *active*

---

## Finance

### Budgeting & Accounting

- **[Fingrom](https://github.com/lyskouski/app-finance)** — Platform-agnostic open-source financial accounting application and one of the most active finance apps in Flutter. `AGPL-3.0` · Android, iOS, Windows, Linux, macOS, Web · *active*
- **[Monekin](https://github.com/enrique-lozano/Monekin)** — "Track your money, not your data" — offline-first, zero-telemetry personal finance. `AGPL-3.0` · Android, iOS, Linux, Windows, macOS, Web · *active*
- **[Cashew](https://github.com/jameskokoska/Cashew)** — Budget and purchase manager, one of the most-starred Flutter finance apps. `GPL-3.0` · Android, iOS, macOS, Windows, Linux · *active*
- **[Oinkoin](https://github.com/emavgl/oinkoin)** — Expense manager that requires no internet. `GPL-3.0` · Android, iOS, Web, Linux, Windows, macOS · *active*
- **[BeeCount](https://github.com/TNT-Likely/BeeCount)** — Local-first bookkeeping with self-hosted / iCloud / WebDAV / S3 sync. *(non-standard license)* · iOS, Android, Web · *active*
- **[Sossoldi](https://github.com/RIP-Comm/sossoldi)** — Free and open wealth-management / net-worth tracking. `MIT` · Android, iOS · *active*
- **[CashBalancer](https://github.com/bernaferrari/cashbalancer)** — Asset-allocation and balancing calculator across multiple accounts. `Apache-2.0` · Android, iOS, Linux, Windows, macOS, Web · *active*
- **[piggyvault](https://github.com/piggyvault/piggyvault)** — Family finance management. `MIT` · Android, iOS, Web · *active*

### Invoicing, POS & Trading

- **[Invoice Ninja (Flutter)](https://github.com/invoiceninja/flutter)** — Flutter client for the Invoice Ninja invoicing platform. `AGPL-3.0` · Android, iOS, Windows, Linux, macOS · *active, beta*
- **[Invoiso](https://github.com/Anooppandikashala/invoiso)** — Offline invoice and billing software: PDF invoices, quotations, customers, products, CSV export. `MIT` · Windows, Linux · *active*
- **[flutter-pos-system](https://github.com/evan361425/flutter-pos-system)** — Offline-first POS for small restaurants: ingredient inventory, menu, orders, Bluetooth receipt printing, Google Sheets export. `Apache-2.0` · Android, iOS, Web · *active*
- **[MarketMonk](https://github.com/brandonp2412/marketmonk)** — Cross-platform stock and portfolio tracker. `MIT` · Android, iOS, Web, Linux, Windows, macOS · *active*

### Crypto Wallets

- **[Cake Wallet](https://github.com/cake-tech/cake_wallet)** — Non-custodial multi-currency wallet (also ships Monero.com), a flagship Flutter crypto project. `MIT` · Android, iOS, macOS, Windows, Linux, Web · *active*
- **[Breez Mobile](https://github.com/breez/breezmobile)** — Lightning Network mobile client for instant bitcoin payments, migrating toward the Greenlight SDK. `GPL-3.0` · Android, iOS · *active*
- **[Gleec Wallet](https://github.com/GLEECBTC/gleec-wallet)** — Non-custodial mobile Bitcoin/Lightning wallet. `GPL-3.0` · Android, iOS · *active*
- **[Archethic Wallet](https://github.com/archethic-foundation/archethic-wallet)** — Fully decentralized hot wallet for the Archethic L1 blockchain. `AGPL-3.0` · Android, iOS · *slowing*
- **[Encointer Wallet](https://github.com/encointer/encointer-wallet-flutter)** — Wallet for the Encointer community-currency blockchain. `Apache-2.0` · Android, iOS, Web · *active*
- **[Natrium](https://github.com/appditto/natrium_wallet_flutter)** — Fast, secure NANO wallet. ⚠️ *Elastic License 2.0, not open source* · Android, iOS · *stale*
- **[AgoraDesk](https://github.com/agoradesk-localmonero/agoradesk-app-foss)** — P2P Monero trading app (buy/sell without ID verification). `Apache-2.0` · Android, iOS · *slowing*

---

## Health, Fitness & Mental Health

- **[wger Workout Manager](https://github.com/wger-project/flutter)** — Fitness and workout tracker that syncs with the self-hosted wger server. `AGPL-3.0` · Android, iOS, Web · *very active*
- **[Medito](https://github.com/meditohq/medito-app)** — Permanently free, ad-free meditation app with courses and themed packs, run by the Medito Foundation. `AGPL-3.0` · Android, iOS · *very active*
- **[OpenNutriTracker](https://github.com/simonoppowa/OpenNutriTracker)** — Privacy- and simplicity-focused calorie and nutrition tracker. `GPL-3.0` · Android, iOS, Linux, macOS, Windows, Web · *very active*
- **[Energize](https://codeberg.org/epinez/energize)** — Very fast nutrition and food tracking app; notable for being Codeberg-hosted and F-Droid-listed. **Codeberg** · Android, iOS, Linux, Windows, macOS, Web · *active*
- **[Open Food Facts](https://github.com/openfoodfacts/smooth-app)** — Barcode scanner and food database companion for the 3M+ product open database. `Apache-2.0` · Android, iOS · *very active*
- **[Track My Indoor Workout](https://github.com/TrackMyIndoorWorkout/TrackMyIndoorWorkout)** — Records workouts from BLE fitness machines: bike, treadmill, rower, ergometer, elliptical. `Apache-2.0` · Android, iOS · *active*
- **[OpenHIIT](https://github.com/a-mabe/OpenHIIT)** — Cross-platform HIIT and Tabata interval timer. `MIT` · Android, iOS · *active*
- **[blood-pressure-monitor-fl](https://github.com/derdilla/blood-pressure-monitor-fl)** — Blood-pressure diary with customizable export and Bluetooth device input. `GPL-3.0` · Android, iOS, Web, Linux, Windows, macOS · *active*
- **[trale](https://github.com/quantumphysique/trale)** — Minimal, privacy-respecting body-weight diary. `AGPL-3.0` · Android, iOS, Web · *active*
- **[Menstrudel](https://github.com/J-shw/Menstrudel)** — Free, offline, open-source period tracking. `GPL-3.0` · Android, iOS · *active*
- **[Fitbook](https://github.com/brandonp2412/fitbook)** — Offline-first calorie/nutrition tracker with barcode scanning and macro graphs. `MIT` · Android, iOS, Web · *active*
- **[ExHale](https://codeberg.org/retiolus/exhale)** — Quit-smoking companion. **Codeberg** · Android, iOS · *slowing*
- **[HealthWallet.me](https://github.com/LifeValue/HealthWallet.me)** — Patient-controlled FHIR R4 health record manager with on-device LLM document scanning, aggregating 52K+ US providers. `GPL-3.0` · Android, iOS · *active*
- **[Nepanikar (Don't Panic)](https://github.com/Nepanikar/nepanikar)** — Psychological first aid app, consulted with mental-health professionals. `MIT` · Android, iOS, Web · *active*
- **[PinkRain](https://github.com/rudi-q/pinkrain_health_journal)** — Privacy-first mental-health companion: symptom journaling, medication management, emotional support. `AGPL-3.0` · Android, iOS · *active*
- **[StudyU](https://github.com/studyu-health/studyu)** — Platform for authoring, publishing and running patient-led N-of-1 trials. `MIT` · Android, iOS, Web · *very active*
- **[Apexo](https://github.com/alselawi/apexo-flutter)** — Offline-first dental clinic management with multi-device sync. `GPL-3.0` · Android, iOS · *slowing*

---

## Education & Learning

- **[Helium](https://github.com/HeliumEdu/frontend)** — Color-coded student planner for classes, homework, grades and notes with multi-device sync. `Apache-2.0` · Android, iOS, Web, macOS, Windows, Linux · *very active*
- **[Saber](https://github.com/saber-notes/saber)** — Cross-platform open-source app built for handwriting: scribble, whiteboard, custom brushes. `GPL-3.0` · Android, iOS, Windows, Linux, macOS, Web · *active*
- **[Sharezone](https://github.com/SharezoneApp/sharezone-app)** — Collaborative school-organization app with 500k+ downloads. `EUPL-1.2` · iOS, Android, macOS, Web · *active*
- **[freeCodeCamp mobile](https://github.com/freeCodeCamp/mobile)** — freeCodeCamp's official open-source app for learning to code. `BSD-3-Clause` · Android, iOS · *active*
- **[CircuitVerse Mobile](https://github.com/circuitverse/mobile-app)** — Official mobile app for the CircuitVerse circuit-simulation platform. `MIT` · Android, iOS, Web · *active*
- **[Lapse](https://github.com/Pairadux/lapse)** — Cross-platform flashcard app using the FSRS scheduler, with nested decks, offline SQLite and a custom desktop UI. `GPL-3.0` · Linux, macOS, Windows, Android, iOS · *active*
- **[NATINFo](https://codeberg.org/retiolus/natinfo_flutter)** — Search and consult the current NATINF nomenclature violations. **Codeberg** · Android, iOS, Web · *active*
- **[Wuxia Learn](https://github.com/wuxialearn/wuxialearn)** — Free and open-source Chinese language learning app. `MIT` · Android, iOS, Web · *slowing*
- **[Vocabhub](https://github.com/maheshj01/vocabhub)** — Vocabulary builder with 800+ curated GRE words. `Apache-2.0` · Android, iOS · *active*
- **[words.hk](https://github.com/alienkevin/wordshk_app)** — Open Cantonese dictionary. `MIT` · Android, iOS · *slowing*
- **[OpenUSOS](https://github.com/openusos/openusos)** — Unofficial USOS academic-system app for students in Poland. `GPL-3.0` · Android, iOS · *slowing*
- **[Fun with Kanji](https://github.com/krille-chan/fun-with-kanji)** — Learn Hiragana, Katakana and Kanji writing systems (same author as FluffyChat). `MPL-2.0` · Android, iOS, Web · *stale*

---

## E-Commerce, Food & Storefronts

- **[WooCommerce Flutter App](https://github.com/woosignal/flutter-woocommerce-app)** — Ready-made template that turns a WooCommerce store into an iOS/Android app. `BSD-2-Clause` · Android, iOS · *active*
- **[based cooking](https://github.com/binabh/based-cooking-app)** — Client app for the based.cooking open recipe site. `CC0-1.0` · Android, iOS, Web · *active*
- **[Shopping List](https://github.com/jaimegonzalezfabregas/lista_de_la_compra)** *(F-Droid: `es.antonborri.lista_de_la_compra`)* — F-Droid-published shopping list with integrated meal planning. *(no license file)* · Android · *active*
- **[Flutter Games storefront](https://github.com/rayliverified/FlutterGames)** — Game storefront for purchasing and renting games (DRM-free / keys model). `0BSD` · Android, iOS, Web · *active*
- **[Grocery-App](https://github.com/Widle-Studio/Grocery-App)** — Grocery shopping app for mobile and web. `MIT` · Android, iOS, Web · *stale*

---

## Maps, Transit & Field Data

### OpenStreetMap & Field Data

- **[Every Door](https://github.com/zverik/every_door)** — Dedicated app for collecting and editing thousands of POIs for OpenStreetMap. `GPL-3.0` · Android, iOS, Web · *active*
- **[OpenStop](https://github.com/opener-next/openstop)** — Collects OpenStreetMap-compliant public-transport accessibility data. `GPL-3.0` · Android, iOS, Web · *active*
- **[qr_wallet](https://github.com/v0l/qr_wallet)** — Offline wallet for loyalty cards, tickets and QR/barcodes, with a pure-Dart ZXing fallback for desktop. `MIT` · Android, iOS, macOS, Linux, Windows, Web · *active*

### Navigation & Routing

- **[bike-gps](https://github.com/patrick-mahnkopf/bike-gps)** — Cross-platform bike navigation system powered by OpenStreetMap, Mapbox GL, and OpenMapTiles. `BSD-3-Clause` · Android, iOS · *active*
- **[Trailblaze](https://github.com/andreytakhtamirov/trailblaze)** — Scenic route planner for cycling with turn-by-turn navigation and gravel routing. `Apache-2.0` · Android, iOS · *active*
- **[HordMaps](https://github.com/HordRicJr/HordMaps)** — Navigation app with Azure Maps: real-time GPS, voice guidance, offline caching, multi-modal routing. `MIT` · Android · *active*
- **[nav-e](https://github/Navware-Official/nav-e)** — Navigation engine with GPS tracking, Bluetooth device management, and intelligent route planning. `GPL-3.0` · Android · *active*
- **[SmartRoute](https://github.com/majharul-islam181/SmartRoute)** — OSM route planning with OSRM routing engine, clean architecture, and Material Design 3. `MIT` · Android, iOS · *active*
- **[Fluttair](https://github.com/acrovato/fluttair)** — VFR flight planning and navigation moving map for pilots. `GPL-3.0` · Android, iOS · *stale*

### Outdoor & GPS Tracking

- **[RunFlutterRun](https://github.com/BenjaminCanape/RunFlutterRun)** — Strava-like tracker for running, walking, and cycling with real-time map and voice synthesis. `MIT` · Android, iOS · *active*
- **[RunTiyul](https://github.com/nachem/runTiyul)** — Offline-first trail running: maps, GPX routes, GPS recording, and on-route navigation. `MIT` · Android, iOS · *active*
- **[car-tracker-flutter](https://github.com/tentone/car-tracker-flutter)** — GPS car tracker for SMS-based Chinese devices (A11, ST-901, GT01, GT09). `MIT` · Android · *active*
- **[wanderer-frontend](https://github.com/tomassirio/wanderer-frontend)** — Real-time pilgrimage and trip tracking with interactive maps. *(no license file)* · Android, iOS, Web · *active*
- **[gridwalker](https://github.com/ceakins/gridwalker)** — Search & rescue with offline maps, GPS tracking, and P2P mesh sync. `MIT` · Android, iOS · *active*
- **[Apex](https://github.com/Purukitto/apex-app)** — Motorcycle companion: GPS ride tracking, garage management, fuel logs, and maintenance. `GPL-3.0` · Android · *active*
- **[Off](https://github.com/DanieleGiovanardi2408/off)** — Enduro/off-road rider companion with offline maps, GPS tracking, and route planning. *(license in repo)* · Android, iOS · *active*

### Marine & Boating

- **[BoatOS](https://github.com/bigbrainlabs/BoatOS)** — Marine navigation system for Raspberry Pi: AIS, offline charts, routing, and sensor dashboard. `GPL-3.0` · Linux (Raspberry Pi) · *active*
- **[Sakkoja](https://github.com/traali/sakkoja)** — Offline-first boating safety app for Finnish waterways with weather radar and restrictions. `MIT` · Android · *active*
- **[OpenCPN NextGen](https://github.com/maritime-datasystems/opencpn_next_gen)** — Mobile vector chart plotter with S-57 ENC support and live GPS/AIS overlay. `GPL-2.0` · Android · *active*
- **[Boat Instrument](https://github.com/philseeley/boatinstrument)** — SignalK marine instrument dashboard with fully configurable boxes. `GPL-3-0` · Android, iOS, Web · *active*
- **[Nautica](https://github.com/valeriopezone/nautica)** — Marine dashboard for SignalK sensors: GPS, wind, depth, heading, and more. *(no license file)* · Android, iOS · *active*

### Public Transit

- **[Trufi Core](https://github.com/trufi-association/trufi-core)** — Multi-modal public transport app framework with GTFS, OSM, and OpenTripPlanner. `GPL-3.0` · Android, iOS · *very active*
- **[Transito](https://github.com/techsupportz/transito-flutter)** — Singapore bus timing app with real-time arrivals from LTA DataMall. `GPL-3.0` · Android, iOS · *active*
- **[bussin](https://github.com/grubk/bussin)** — Vancouver bus tracking with GTFS-RT, live vehicle positions, and ETAs. `GPL-3.0` · Android, iOS · *active*
- **[Prevoz](https://github.com/vualeks/prevoz)** — Podgorica public transit tracker with live bus locations and routes. `MIT` · Android, iOS · *active*
- **[Bus Tracking Flutter](https://github.com/thisislohit/bus-tracking-flutter)** — Crowdsourced bus tracking with Google Maps and Firebase. *(no license file)* · Android · *active*

### Weather & Radar

- **[Rain](https://github.com/darkmoonight/Rain)** — Feature-rich weather app with OSM map, radar, air quality, and 38 languages. `MIT` · Android · *very active*
- **[Overmorrow](https://github.com/bmaroti9/Overmorrow)** — Material Design weather app with precipitation radar and 72-hour forecast. `GPL-3.0` · Android · *very active*
- **[Pluvia](https://github.com/SpicyChair/pluvia_weather_flutter)** — Weather app with beautiful animations, Mapbox search, and weather radar. `GPL-3.0` · Android · *active*
- **[Cuaca](https://github.com/lingyee/cuaca)** — Malaysia weather app with live rain radar and OSM base map. `MIT` · Android · *active*

### Aviation

- **[Aero](https://github.com/phantomknight287/aero)** — Real-time flight tracking with interactive path visualization and Wear OS companion. *(license in repo)* · Android, iOS · *active*
- **[Flight Tracker](https://github.com/sandyandoss/Flight-Tracker)** — Live flight tracking with Google Maps and AviationStack API. *(no license file)* · Android, iOS · *active*
- **[Pilot Logbook](https://github.com/ken340/pilot-logbook)** — Offline-first pilot logbook with flight map visualization and statistics. `MIT` · Android, iOS · *active*
- **[Flight Radar Widget](https://github.com/Puffin-Programs/Flight_Radar_Widget)** — Desktop flight radar with PPI sweep and OSM map view. `MIT` · Windows, macOS, Linux · *active*

### Map Engines & Toolkits

These are libraries, not apps, but many open-source Flutter map apps above are built on them.

- **[flutter_map](https://github.com/fleaflet/flutter_map)** — Flutter's #1 non-commercial map client: easy-to-use, versatile, vendor-free, fully cross-platform, and 100% pure-Flutter. `BSD-3-Clause` · all platforms · *very active*
- **[flutter_osm_plugin](https://github.com/liodali/osm_flutter)** — Full OpenStreetMap plugin with markers, roads, tracking, and custom tiles. `MIT` · Android, iOS, Web · *active*
- **[mapbox_maps_flutter](https://github.com/mapbox/mapbox-maps-flutter)** — Official Mapbox Maps SDK for Flutter with highly customizable vector maps. *(Mapbox license)* · Android, iOS · *active*
- **[flutter_map_tile_caching](https://github.com/JaffaKetchup/flutter_map_tile_caching)** — Advanced offline tile caching and bulk downloading for flutter_map. `GPL-3.0` · all platforms · *active*

---

## Games

> The open-source Flutter game ecosystem skews towards tutorials, hackathon entries and jam games. Those that are genuinely finished or still maintained are listed here; abandoned ones are in [Notable but Unmaintained](#notable-but-unmaintained).

### Board & Card Games

- **[Lichess Mobile](https://github.com/lichess-org/mobile)** — Second-iteration Flutter client for lichess.org: play, puzzles, analysis, tournaments, with Stockfish via `multistockfish`. `GPL-3.0` · iOS, Android · *very active*
- **[Tri Peaks NEUE](https://github.com/mimoguz/tripeaks_neue)** — Solitaire variant with multiple layouts and game options. `AGPL-3.0` · Android, iOS · *very active*
- **[Pegma](https://github.com/khlebobul/pegma)** — Cross-platform Peg Solitaire. `MIT` · Android, iOS, Web, desktop · *very active*
- **[Chinese Chess (Xiangqi)](https://github.com/shirne/chinese_chess)** — Full Chinese Chess implementation with board and AI. `GPL-2.0` · Android, iOS · *active*
- **[fludo](https://github.com/smokelaboratory/fludo)** — Ludo board game rendered directly with Flutter Canvas, no game engine. `Apache-2.0` · Android, iOS · *maintained*

### Arcade, Puzzle & Action

- **[Save The Potato](https://github.com/imaNNeo/save_the_potato)** — Rotate-shields arcade game; winner of Flame Game Jam 3.0. *(license in repo)* · Android, iOS · *active*
- **[Squareshooter Flame](https://github.com/namzug16/squareshooter_flame)** — Top-down web shooter with AI enemies driven by behavior trees (player vs AI or AI vs AI). `MIT` · Web · *maintained*
- **[Antimine](https://github.com/lucasnlm/antimine-flutter)** — Open-source Minesweeper-like puzzle game. `AGPL-3.0` · Android, desktop · *maintained*

### Roguelikes & Strategy

- **[Age of New Worlds](https://github.com/ernestwisniewski/aonw)** — Open-source turn-based 4X strategy on a hex map: Flutter + Flame client, pure-Dart rules, Serverpod backend. *(license in repo)* · mobile, desktop · *active*
- **[Emberdelve](https://github.com/tapiwamakandigona/emberdelve)** — Dice-builder roguelite pivoted to a pixel action-platformer, with a pure-Dart headless-tested economy layer. *(license in repo)* · Android · *active*
- **[Darkness Dungeon](https://github.com/RafaelBarbosatec/darkness_dungeon)** — Simple 2D RPG dungeon crawler and the original testbed for the Bonfire package. `MIT` · Android, Web · *maintained*

### Game Engines & Toolkits

These are libraries, not apps, but every open-source Flutter game above is built on one of them.

- **[Flame](https://github.com/flame-engine/flame)** — The dominant 2D game engine for Flutter: game loop, component system, particles, collision, sprites, plus ~15 first-party bridge packages. `MIT` · all platforms · *very active*
- **[Rive](https://github.com/rive-app/rive-flutter)** — State-machine-driven vector animation runtime and renderer, with a GameKit for 120fps vector scenes. `MIT` · all platforms · *active*
- **[Bonfire](https://github.com/RafaelBarbosatec/bonfire)** — RPG-maker layer on top of Flame: player/enemy/NPC components, Tiled maps, behavior trees, pathfinding, lighting. `MIT` · all platforms · *active*
- **[Forge2D](https://github.com/flame-engine/forge2d)** — Box2D 2.x physics ported to Dart, maintained by the Flame team. `MIT` · all platforms · *active*
- **[Flutter Casual Games Toolkit](https://github.com/flutter/games)** — Google's official template set: endless runner, puzzle and card-game templates with audio, lifecycle and level scaffolding. `Apache-2.0` · web, mobile · *active*
- **[Good](https://github.com/sunarya-thito/good)** *(in `packages/good`)* — ECS kernel running the simulation on its own isolate with components in shared native memory. `BSD-3-Clause` · mobile, desktop · *active, early*
- **[Just Game Engine](https://github.com/just-unknown-dev/just-game-engine)** — ECS-first alternative to Flame: fixed-timestep loop, impulse physics with SAT and spatial grid, raycasting, Tiled support. `BSD-3-Clause` · all platforms · *active, WIP*

### Google / VGV Showcase Games (open source, frozen)

These are finished, polished, fully open-source games — but Google has stopped committing to them. They are
still the best reference implementations of "what a complete Flutter game looks like".

- **[I/O Pinball](https://github.com/VGVentures/pinball)** — Google I/O 2022 pinball built with Flutter, Firebase, Flame and Forge2D, with a live global leaderboard on Cloud Firestore. *(license: VGV)* · web · *frozen since 2023*
- **[I/O FLIP](https://github.com/VGVentures/io_flip)** — Google I/O 2023 AI-designed card game, with a Dart Frog server sharing game logic with the Flutter client. *(license: VGV)* · web · *frozen since 2023*
- **[Very Good Ranch](https://github.com/VeryGoodOpenSource/very_good_ranch)** — VGV's own Flame game demo, produced to work out their internal game-development standards. `MIT` · mobile · *frozen since 2023*

---

## Plain Dart (non-Flutter)

Dart's CLI, server and scripting ecosystem. All of these run on the Dart VM without Flutter.

- **[Very Good CLI](https://github.com/VeryGoodOpenSource/very_good_cli)** — Scaffolds Dart/Flutter packages, apps, plugins and CLIs; runs tests and license checks, and exposes an MCP server. `MIT` · CLI · *very active*
- **[puby](https://github.com/Rexios80/puby)** — Run `pub`/`build_runner`/`test`/`clean` across every project in a monorepo, auto-detecting dart/flutter/fvm. `BSD-3-Clause` · CLI · *active*
- **[Taskwarrior terminal client](https://github.com/CCExtractor/taskwarrior-flutter)** — A full terminal task manager written in Dart. `GPL-3.0` · CLI · *active*
- **[tldr-flutter](https://github.com/techno-disaster/tldr-flutter)** — Simplified man-pages client for tldr.sh, also usable as a plain CLI. `MIT` · CLI, Android · *very active*
- **[mimic](https://github.com/vladimir120307-droid/mimic)** — Turn a screen recording or screenshot into working Flutter/HTML/React code. `MIT` · CLI · *active*
- **[BendyStraw](https://codeberg.org/mm-dev/bendy-straw)** — Manages and imports NewPipe databases; usable headless for scripted migrations. **Codeberg** · Android, CLI · *active*
- **[dart_jellyfin](https://github.com/ales-drnz/dart_jellyfin)** — Pure-Dart Jellyfin client library: auth, library browsing, playlists, streaming. `BSD-3-Clause` · Dart VM · *active*
- **[dart_plex](https://github.com/ales-drnz/dart_plex)** — Pure-Dart Plex Media Server client library: auth, library browsing, playlists. `BSD-3-Clause` · Dart VM · *active*
- **[Bullseye2D](https://github.com/bullseye2d/bullseye2d)** — Pure-Dart 2D engine with a WebGL2 web backend and a native SDL3 desktop backend — no Flutter dependency. *(verify license)* · web, Windows, macOS, Linux · *beta*

---

## Notable but Unmaintained

Listed for historical reference and because they are still good reading. None of these have had a commit
in roughly two years or more, so do not expect builds, fixes or security updates.

- **[pocket_dungeons](https://github.com/Bluefireteam/pocket-dungeons)** *(Flutter project in `game/`)* — A turn-based dungeon-crawling roguelike by the Flame lead. Abandoned since 2019, still the canonical Flame roguelike reference.
- **[I/O Pinball / I/O FLIP / Very Good Ranch](https://github.com/VGVentures/pinball)** — see the [showcase games section](#google--vgv-showcase-games-open-source-frozen).
- **[dino_run](https://github.com/ufrshubham/dino_run)** — Chrome-dinosaur-style infinite side-scroller on Flame, and the most-starred Flame game. `MIT` · frozen since 2021. Built against Flame pre-1.0, will not compile against current Flame.
- **[spacescape](https://github.com/ufrshubham/spacescape)** — 2D top-down space shooter. `MIT` · last commit 2025. Same author and tutorial series as `dino_run`.
- **[BGUG](https://github.com/fireslime/bgug)** — Robot-and-guns side-scrolling platformer; the best complete "everything Flame can do" showcase. `MIT` · frozen since 2020.
- **[Ghost Rigger](https://github.com/Float-like-a-dash-Sting-like-a-dart/GhostRigger)** — Cyberpunk puzzle prototype from a hackathon. `MIT` · web · frozen since 2020.
- **[FlutterSolitaire](https://github.com/d3xvn/FlutterSolitaire)** — Solitaire clone. No license declared. Abandoned since 2019.
- **[Fritter](https://github.com/jonjomckay/fritter)** — Twitter frontend. See [Social & Fediverse](#social--fediverse).
- **[Flutter Novel](https://github.com/lwlizhe/flutter_novel)** — Chinese novel reader with page-flip animations. `BSD-3-Clause` · last commit 2024.
- **[Harpy](https://github.com/robertodoering/harpy)** — Task manager with a distinctive Material You design. `GPL-3.0` · frozen since 2023.
- **[Noteless](https://github.com/redsolver/noteless)** — Minimal Markdown notes. `MIT` · archived 2021.
- **[Fedi](https://github.com/Big-Fig/Fediverse.app)** — Pleroma + Mastodon client. `AGPL-3.0` · last commit 2022.
- **[Syphon](https://github.com/syphon-org/syphon)** — Non-profit, privacy-centric Matrix client. `AGPL-3.0` · last commit 2023.
- **[Githo](https://github.com/glitchy-tozier/githo)** — Gradual habit builder. `GPL-3.0` · frozen since 2022.
- **[sharik](https://github.com/marchellodev/sharik)** — Cross-platform Wi-Fi file sharing. `MIT` · last commit 2022.
- **[Afrodite](https://github.com/afroditeapp/afrodite-frontend)** — Ethical open-source dating app with privacy-focused browsing and E2EE chat. `Apache-2.0` · pre-production, not ready for use.

---

## Related Lists & Directories

### Flutter and Dart lists

- **[Awesome Flame](https://github.com/flame-engine/awesome-flame)** — *The* canonical list for Flame: games by genre, libraries, tutorials and articles. The closest upstream relative of this repository.
- **[Solido/awesome-flutter](https://github.com/Solido/awesome-flutter)** — The biggest Flutter awesome list (~59k stars), with libraries, plugins and an open-source apps section.
- **[nepaul/awesome-flutter](https://github.com/nepaul/awesome-flutter)** — Heavily app-focused Flutter taxonomy, including a desktop-only section.
- **[awesome-dart](https://github.com/yissachar/awesome-dart)** — Dart-language-level libraries and frameworks, including a game development section.
- **[awesome-flutter-packages](https://github.com/simc/awesome-flutter-packages)** — Package directory organized by category.
- **[awesome-open-source-flutter-apps](https://github.com/fluttergems/awesome-open-source-flutter-apps)** — Table of OSS Flutter apps with a large games category (~980 rows). Paired with [fluttergems.com](https://fluttergems.com/).
- **[awesome.ecosyste.ms — topic: flutter](https://awesome.ecosyste.ms/lists?topic=flutter)** — Index of every awesome list tagged Flutter.

### App directories worth cross-checking

- **[Open Apps](https://github.com/tortuvshin/open-apps)** — Human-curated directory of real production OSS apps with review notes, now spanning Flutter/Kotlin/Swift/RN/Tauri. Site: [openappscout.com](https://openappscout.com).
- **[F-Droid](https://f-droid.org/)** — The definitive free/open-source Android index. If an app claims to be FOSS, this is where you check.
- **[Flathub](https://flathub.org/apps)** — The Linux desktop store; where the Flutter/Linux apps above actually ship.
- **[Open-Source iOS Apps](https://github.com/dkhamsing/open-source-ios-apps)** (~1,600 apps, 50k stars) and **[Open-Source Android Apps](https://github.com/pcqpcq/open-source-android-apps)** (~800 apps, with language and license columns) — good for spotting `Dart` entries.
- **[awesome-mobile-apps](https://github.com/devxhub/awesome-mobile-apps)** — Aggregates the iOS, Android, Flutter and React Native lists into one index.

### Games and engine references

- **[Flame docs and showcase](https://docs.flame-engine.org)** and **[Made with Flame](https://flame-engine.org/)** — Engine docs plus the official wall of games built with it (many source-closed).
- **[Flame examples](https://examples.flame-engine.org/)** — Runnable browser demos for every Flame feature; the best learning reference.
- **[Flame Game Jam](https://itch.io/jam/flame-game-jam-2026)** — Annual open-source-only jam. Every entry is required to have public source, so submissions are verifiable.
- **[Games in Flutter](https://gamesinflutter.com/)** — Community catalog of Flutter games by genre. Small project; verify links before citing.
- **[Flutter Showcase](https://flutter.dev/showcase)** — Google's official case studies of production Flutter apps. Mostly source-closed, but the canonical citation for "Flutter ships at scale".

---

## Contributing

Pull requests are welcome. To keep this list trustworthy, entries are held to a fairly high bar:

**A new app qualifies if it is:**

1. **An app, not a package.** A repo whose root is a `pubspec.yaml` with a runnable app target, or a CLI tool for [Plain Dart](#plain-dart-non-flutter). Libraries and plugins belong on an awesome-*packages* list, not here — with the deliberate exception of [game engines](#game-engines--toolkits), which exist only to give games an engine.
2. **Genuinely built with Dart or Flutter.** If your repo has a `pubspec.yaml` in its git tree, it qualifies. If it does not, it does not — regardless of what the README claims. (This rule caught at least one popular "Flutter" app that turned out to be an Ionic/Capacitor project.)
3. **Open source under a recognized license,** with the license file actually present in the repo. Copyleft (`AGPL-3.0`, `GPL-3.0`) and copyleft-adjacent (`MPL-2.0`) are strongly encouraged. Source-available licenses such as `Elastic License 2.0` or custom EULAs are **not** eligible for the main list; if you think one belongs, propose it for the Highlights-adjacent notes with an explicit warning.
4. **Freely installable,** or at minimum buildable from source with documented instructions. A closed beta with no public build does not qualify.
5. **Not a tutorial, demo, portfolio project or template.** "Build a chat app in Flutter" tutorial repos are the single largest source of noise in this ecosystem and are the main reason most competing lists go stale. If it teaches, it belongs in the [related lists](#related-lists--directories).
6. **Hosted on GitHub or Codeberg.** For other forges, please open an issue first so we can decide on a consistent format rather than ad-hoc links to dozens of one-off instances.
7. **Not already listed.** Search the whole README first, including
   [Notable but Unmaintained](#notable-but-unmaintained) — a revived project should be moved up, not duplicated.

**Please include in your PR:** the direct link to the repository, the license, which platforms are
actually built and released (not merely targeted), and a single sentence on what the app does. If the app
is distributed anywhere, add that too (F-Droid, Flathub, Play Store, App Store, itch.io) — it is a
strong signal of maturity.

**Stale entries are not deleted, they are moved** to
[Notable but Unmaintained](#notable-but-unmaintained). If you maintain a project listed as stale,
please open a PR saying so — that is always welcome news.

---

## License

This list is released under [CC0 1.0 Universal](LICENSE). The applications it links to are each licensed
by their own authors under the terms shown in their entry; check the linked repository before using any
of them.
