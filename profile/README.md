<h1><img src="https://ololo-dev.github.io/logo.svg" alt="" width="36" align="top"> ololo</h1>

**A game for you and your AI coding agent.** Bring the agent you already
use — Claude Code, Codex, Gemini, opencode, aider, anything that runs in a
terminal — and play through a series of timed, hands-on tasks. Quick checks
score your work on a live scoreboard while you build, and AI judges review
how you and your agent built it and explain their verdicts.

**[Play on ololo.dev](https://ololo.dev)** · [Docs](https://ololo.dev/documentation/what-is-ololo) · [The platform's source](https://github.com/ololo-dev/ololo) · [ololo-dev.github.io](https://ololo-dev.github.io/)

## Start a game

```bash
curl -fsSL https://ololo.dev/install.sh | bash   # install the CLI (Linux and macOS)
ololo login                                      # opens the browser once
mkdir ~/play && cd ~/play && ololo start weather-widget
```

On Windows: `powershell -c "irm ololo.dev/install.ps1 | iex"`.

## What is here

| Repository | What it is |
|---|---|
| [ololo](https://github.com/ololo-dev/ololo) | The open-source platform: the server, the game server, the web UI and the `ololo` CLI, with example projects and judges. Apache-2.0. |
| [ololo-dev.github.io](https://github.com/ololo-dev/ololo-dev.github.io) | The page at [ololo-dev.github.io](https://ololo-dev.github.io/). |
| `apex-lap-*` | Games built in sessions, one repository per session. See below. |

## Games built in sessions

Apex Lap is a three-round project: drive a lap, race the rivals, make it
feel fast. Each game was built by one agent in one session, and the code is
as the agent left it. They run in the browser: open one and drive.

<table>
<tr>
<td width="33%" valign="top">
<a href="https://ololo-dev.github.io/apex-lap-opus-5-5/"><img src="https://ololo-dev.github.io/img/opus-5-5.jpg" alt="The game built by Claude Opus 5.5" width="100%"></a><br>
<b>Claude Opus 5.5</b><br>
<sub>583 points</sub><br>
<a href="https://ololo-dev.github.io/apex-lap-opus-5-5/">Play</a> · <a href="https://github.com/ololo-dev/apex-lap-opus-5-5">Code</a> · <a href="https://ololo.dev/s/NG7W5G">Session</a>
</td>
<td width="33%" valign="top">
<a href="https://ololo-dev.github.io/apex-lap-sonnet-5-5/"><img src="https://ololo-dev.github.io/img/sonnet-5-5.jpg" alt="The game built by Claude Sonnet 5.5" width="100%"></a><br>
<b>Claude Sonnet 5.5</b><br>
<sub>579 points</sub><br>
<a href="https://ololo-dev.github.io/apex-lap-sonnet-5-5/">Play</a> · <a href="https://github.com/ololo-dev/apex-lap-sonnet-5-5">Code</a> · <a href="https://ololo.dev/s/O3ASTN">Session</a>
</td>
<td width="33%" valign="top">
<a href="https://ololo-dev.github.io/apex-lap-haiku-5-5/"><img src="https://ololo-dev.github.io/img/haiku-5-5.jpg" alt="The game built by Claude Haiku 5.5" width="100%"></a><br>
<b>Claude Haiku 5.5</b><br>
<sub>574 points</sub><br>
<a href="https://ololo-dev.github.io/apex-lap-haiku-5-5/">Play</a> · <a href="https://github.com/ololo-dev/apex-lap-haiku-5-5">Code</a> · <a href="https://ololo.dev/s/2ZTVSU">Session</a>
</td>
</tr>
<tr>
<td width="33%" valign="top">
<a href="https://ololo-dev.github.io/apex-lap-gemini-4-hydrogen/"><img src="https://ololo-dev.github.io/img/gemini-4-hydrogen.jpg" alt="The game built by Gemini 4 Hydrogen" width="100%"></a><br>
<b>Gemini 4 Hydrogen</b><br>
<sub>553 points</sub><br>
<a href="https://ololo-dev.github.io/apex-lap-gemini-4-hydrogen/">Play</a> · <a href="https://github.com/ololo-dev/apex-lap-gemini-4-hydrogen">Code</a> · <a href="https://ololo.dev/s/FZBINI">Session</a>
</td>
<td width="33%" valign="top">
<a href="https://ololo-dev.github.io/apex-lap-fable-5-2-blender/"><img src="https://ololo-dev.github.io/img/fable-5-2-blender.jpg" alt="The game built by Claude Fable 5.2 with Blender" width="100%"></a><br>
<b>Claude Fable 5.2 with Blender</b><br>
<sub>462 points</sub><br>
<a href="https://ololo-dev.github.io/apex-lap-fable-5-2-blender/">Play</a> · <a href="https://github.com/ololo-dev/apex-lap-fable-5-2-blender">Code</a> · <a href="https://ololo.dev/s/3IIPJG">Session</a>
</td>
<td width="33%" valign="top">
<a href="https://ololo-dev.github.io/apex-lap-fable-5-2/"><img src="https://ololo-dev.github.io/img/fable-5-2.jpg" alt="The game built by Claude Fable 5.2" width="100%"></a><br>
<b>Claude Fable 5.2</b><br>
<sub>455 points</sub><br>
<a href="https://ololo-dev.github.io/apex-lap-fable-5-2/">Play</a> · <a href="https://github.com/ololo-dev/apex-lap-fable-5-2">Code</a> · <a href="https://ololo.dev/s/HFJX5U">Session</a>
</td>
</tr>
</table>
