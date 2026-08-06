<div align="center">
  <img src="assets/banner.svg" alt="Ezra — Phantom Illusions Studio" width="100%"/>
</div>

<br/>

<div align="center">

<a href="https://archive.phantom-illusions-studio.com/about"><img src="https://img.shields.io/badge/PORTFOLIO-0A0A0F?style=flat-square&logo=todoist&logoColor=C77DFF&labelColor=0A0A0F" /></a>
<a href="https://github.com/mrblaqbeatle"><img src="https://img.shields.io/badge/GITHUB-0A0A0F?style=flat-square&logo=github&logoColor=C77DFF&labelColor=0A0A0F" /></a>
<a href="mailto:REPLACE_WITH_YOUR_EMAIL"><img src="https://img.shields.io/badge/EMAIL-0A0A0F?style=flat-square&logo=maildotru&logoColor=C77DFF&labelColor=0A0A0F" /></a>

</div>

<br/>

```yaml
$ whoami
name: Mwanani Ezra
alias: Mr. Blaq Beatle
based_in: Uganda
role: Software Developer, Co-Founder @ Phantom Illusions Studio
focus:
  - Backend Systems
  - Android Development
  - Web Applications
  - Distributed Systems
  - Real-time Networking
  - UI / UX Design
languages:
  - TypeScript
  - Python
  - Kotlin
  - JavaScript
  - SQL
  - GDScript
  - C++
```

I build complete systems end to end — logic, backend, database, and deployment. Most of my work centers on **backend architecture** and **transaction-safe systems**, extending into **Android development** and, when the project calls for it, **real-time multiplayer engineering**. I also design and produce my own visual assets — branding, UI mockups, promotional art — rather than outsourcing them.

<img src="assets/divider.svg" width="100%"/>

## Phantom Illusions Studio

I'm a **co-founder and software developer** at **Phantom Illusions Studio**, an independent software studio building software products out of Uganda.

**My role:** architecture, backend engineering, and systems development across the studio's products, plus the visual identity work — branding, UI, promotional design — that goes with shipping something.

**Studio Portfolio:** https://archive.phantom-illusions-studio.com/about

<img src="assets/divider.svg" width="100%"/>

## Featured Work

```
$ ls projects/
phantom-lock/       caj-detergents/      aroma-restaurant/      illusion-cli/
```

### `phantom-lock/` — in active development
Android security application for remote device management via SMS commands, built for scenarios where a device needs to be secured or located without an internet connection.

```
STACK     Kotlin, Jetpack Compose
TARGET    SDK 36 (min SDK 30)
STATUS    Active development
```

Android's background execution limits are aggressive, so staying persistent and responsive to SMS commands required a layered defense:

- Fixing `ForegroundServiceStartNotAllowedException` restart paths
- A transparent system overlay anchor to influence OOM priority
- An `AlarmManager`-based watchdog, replacing WorkManager where it wasn't reliable enough
- A deduplicating dynamic `BroadcastReceiver`
- OEM-specific battery optimization handling (MIUI, EMUI, One UI, and others)

---

### `caj-detergents/` — production e-commerce
Production e-commerce site for a local Ugandan business — product showcase, responsive layout, business information pages.
**Live:** https://mrblaqbeatle.github.io/CAJ/

### `aroma-restaurant/` — digital menu experience
Restaurant site focused on digital menu presentation and customer experience.
**Live:** https://mrblaqbeatle.github.io/aroma/index.html

### `illusion-cli/` — experimental
Command-line environment exploring terminal-based workflows and developer tooling.

<img src="assets/divider.svg" width="100%"/>

## Engineering Interests

- Backend architecture
- Transaction-safe systems
- Android systems programming
- Distributed applications
- PostgreSQL and data modeling
- DevOps and deployment

<img src="assets/divider.svg" width="100%"/>

## Stack

```
$ stack --list
```

**backend**
<p> <img src="https://cdn.simpleicons.org/nodedotjs/9D4EDD" width="32" title="Node.js"/> <img src="https://cdn.simpleicons.org/express/9D4EDD" width="32" title="Express"/> <img src="https://cdn.simpleicons.org/postgresql/9D4EDD" width="32" title="PostgreSQL"/> <img src="https://cdn.simpleicons.org/sqlite/9D4EDD" width="32" title="SQLite"/> <img src="https://cdn.simpleicons.org/socketdotio/9D4EDD" width="32" title="WebSockets"/> <img src="https://cdn.simpleicons.org/supabase/9D4EDD" width="32" title="Supabase"/> <img src="https://cdn.simpleicons.org/firebase/9D4EDD" width="32" title="Firebase"/> </p>

**android**
<p> <img src="https://cdn.simpleicons.org/kotlin/9D4EDD" width="32" title="Kotlin"/> <img src="https://cdn.simpleicons.org/jetpackcompose/9D4EDD" width="32" title="Jetpack Compose"/> <img src="https://cdn.simpleicons.org/androidstudio/9D4EDD" width="32" title="Android Studio"/> </p>

**web &amp; languages**
<p> <img src="https://cdn.simpleicons.org/typescript/9D4EDD" width="32" title="TypeScript"/> <img src="https://cdn.simpleicons.org/javascript/9D4EDD" width="32" title="JavaScript"/> <img src="https://cdn.simpleicons.org/python/9D4EDD" width="32" title="Python"/> <img src="https://cdn.simpleicons.org/cplusplus/9D4EDD" width="32" title="C++"/> <img src="https://cdn.simpleicons.org/html5/9D4EDD" width="32" title="HTML5"/> <img src="https://cdn.simpleicons.org/css3/9D4EDD" width="32" title="CSS3"/> </p>

**game development**
<p> <img src="https://cdn.simpleicons.org/godotengine/9D4EDD" width="32" title="Godot Engine"/> </p>

**design**
<p> <img src="https://cdn.simpleicons.org/adobephotoshop/9D4EDD" width="32" title="Photoshop"/> <img src="https://cdn.simpleicons.org/inkscape/9D4EDD" width="32" title="Inkscape"/> <img src="https://cdn.simpleicons.org/gimp/9D4EDD" width="32" title="GIMP"/> </p>

**infrastructure &amp; tools**
<p> <img src="https://cdn.simpleicons.org/git/9D4EDD" width="32" title="Git"/> <img src="https://cdn.simpleicons.org/githubactions/9D4EDD" width="32" title="GitHub Actions"/> <img src="https://cdn.simpleicons.org/docker/9D4EDD" width="32" title="Docker"/> <img src="https://cdn.simpleicons.org/nginx/9D4EDD" width="32" title="Nginx"/> <img src="https://cdn.simpleicons.org/redis/9D4EDD" width="32" title="Redis"/> <img src="https://cdn.simpleicons.org/linuxmint/9D4EDD" width="32" title="Linux Mint"/> </p>

<img src="assets/divider.svg" width="100%"/>

## Design + Code

Most of my projects carry visual work I've done myself — UI mockups, branding, and promotional art built in Photoshop, Inkscape, and GIMP — rather than stock assets. I treat design as part of the engineering process, not a separate step handed off to someone else.

<img src="assets/divider.svg" width="100%"/>

## Stats

<p align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=mrblaqbeatle&show_icons=true&hide_border=true&bg_color=0A0A0F&title_color=C77DFF&icon_color=9D4EDD&text_color=B7B2C6&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mrblaqbeatle&layout=compact&hide_border=true&bg_color=0A0A0F&title_color=C77DFF&text_color=B7B2C6" />
</p>

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=mrblaqbeatle&hide_border=true&background=0A0A0F&stroke=0A0A0F&ring=9D4EDD&fire=C77DFF&currStreakLabel=C77DFF&sideLabels=B7B2C6&currStreakNum=EDEAF6&sideNums=EDEAF6&dates=605B70" />
</p>

<img src="assets/divider.svg" width="100%"/>

```
$ status --current
[ACTIVE]   phantom-lock          Android device recovery application
[ACTIVE]   phantom-illusions     Building software products with co-founders
```

<div align="center">
<br/>
<sub>KAMPALA, UG · <a href="https://archive.phantom-illusions-studio.com/about">PORTFOLIO</a> · <a href="https://github.com/mrblaqbeatle">GITHUB</a></sub>
<br/><br/>
<img src="https://komarev.com/ghpvc/?username=mrblaqbeatle&style=flat-square&color=9D4EDD" alt="profile views" />
</div>
