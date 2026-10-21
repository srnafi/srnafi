<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&color=F8FAFC&center=true&vCenter=true&width=650&lines=I+build+tools+that+fix+annoyances;Desktop+apps+%26+backend+APIs;C%2B%2B+%C2%B7+C%23+%C2%B7+Python+%C2%B7+AI+Evaluation" />
  <img alt="I build tools that fix annoyances" src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1200&color=1F2937&center=true&vCenter=true&width=650&lines=I+build+tools+that+fix+annoyances;Desktop+apps+%26+backend+APIs;C%2B%2B+%C2%B7+C%23+%C2%B7+Python+%C2%B7+AI+Evaluation" />
</picture>

<a href="https://www.linkedin.com/in/srnafi"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-srnafi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a> <a href="mailto:sezarrezanafi@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Get_in_touch-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a> <a href="https://github.com/srnafi?tab=repositories"><img alt="Repositories" src="https://img.shields.io/badge/Repositories-Browse-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

</div>

---

## About

I'm a backend and systems engineer in Dhaka, Bangladesh. Most of what I build starts with an annoyance I face daily, and ends when that annoyance is gone. I care about small binaries, low idle cost and no manual.

- **EX-Expander**: type a shortcode in any app and pick the expansion from a popup. No focus stealing, ~3 MB native build.
- **LingoLens**: snip a region of the screen and read the translation in place, over the original text.
- **Left Right Audio Balancer**: two volume sliders for one output device, so left and right can be set separately. Also fixes Bluetooth headsets that report only one channel.

I have an AI-evaluation background across RLHF, tool-calling and multilingual projects, so I know how models fail and how to test for it.

Open to backend and systems roles, including AI evaluation work.

---

## Featured Projects

### [EX-Expander](https://github.com/srnafi/EX-Expander) [![release](https://img.shields.io/github/v/release/srnafi/EX-Expander?style=flat-square)](https://github.com/srnafi/EX-Expander/releases/latest)

A system-wide text expander for Windows. Type a shortcode in any app, pick from the popup, and the expansion is inserted without stealing focus. You don't have to memorize your own shortcuts.

- ~3 MB native download, ~3% CPU while in active use
- Low-level keyboard hooks, so it works in browsers, editors and games
- GPU-rendered popups (Direct2D) that never take focus
- Per-app scoping, custom trigger characters, auto-start on login
- Clipboard-safe insertion, plus a WebView2 manager for adding and editing expansions

<img alt="C++" src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" /> <img alt="Win32 API" src="https://img.shields.io/badge/Win32_API-0078D4?style=flat-square&logo=windows&logoColor=white" /> <img alt="Direct2D" src="https://img.shields.io/badge/Direct2D-00A4EF?style=flat-square" /> <img alt="WebView2" src="https://img.shields.io/badge/WebView2-3276BC?style=flat-square&logo=microsoftedge&logoColor=white" /> <img alt="SQLite" src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />

<p align="center">
  <img alt="EX-Expander demo: type a shortcode, pick a popup, expansion inserted anywhere" width="85%" src="assets/expander_demo_cropped.gif" />
  <br><sub>Type :hi, pick from the popup, inserted anywhere</sub>
</p>

### [LingoLens](https://github.com/srnafi/LingoLens)

OCR screen translator. Press <kbd>Alt+Shift+M</kbd>, drag a box over any on-screen text, and the translation renders over the original.

- Persistent Flask + EasyOCR backend loads models once, so snips are instant across 20+ languages
- 55% faster OCR through image preprocessing
- Tiered translation fallback (Google, deep-translator, MyMemory) so a snip doesn't fail
- Dark PyQt5 control center for languages, colors, opacity and fonts

<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img alt="PyQt5" src="https://img.shields.io/badge/PyQt5-41CD52?style=flat-square&logo=qt&logoColor=white" /> <img alt="Flask" src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" /> <img alt="EasyOCR" src="https://img.shields.io/badge/EasyOCR-FF6F00?style=flat-square" /> <img alt="OpenVINO" src="https://img.shields.io/badge/OpenVINO-00AEEF?style=flat-square&logo=intel&logoColor=white" /> <img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />

### [Left Right Audio Balancer](https://github.com/srnafi/left-right-audio-balancer) [![release](https://img.shields.io/github/v/release/srnafi/left-right-audio-balancer?style=flat-square)](https://github.com/srnafi/left-right-audio-balancer/releases/latest)

Per-ear volume controller for Windows 10 that sits on your desktop as a widget. The setting exists in Control Panel, several dialogs deep, which makes it useless for anything you adjust more than once. This puts both channels on a desktop card.

- Linked mode holds the offset between the ears, so a balance you set survives the next volume change. Master scales both without breaking it
- Detects Bluetooth headsets that report a single channel, and fixes it by disabling AVRCP absolute volume. The registry write needs admin rights, and the app reads the key back to confirm it landed
- .NET 10 and WPF, single self-contained executable
- Does not disappear on "win + D" press, unlike most win 10 widget apps out there.

<img alt="C#" src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" /> <img alt=".NET" src="https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white" /> <img alt="WPF" src="https://img.shields.io/badge/WPF-512BD4?style=flat-square&logo=windows&logoColor=white" /> <img alt="NAudio" src="https://img.shields.io/badge/NAudio-4B5563?style=flat-square" /> <img alt="Core Audio" src="https://img.shields.io/badge/Core_Audio-0078D4?style=flat-square&logo=windows&logoColor=white" />

---

## Most-used languages

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=srnafi&layout=compact&theme=github_dark&hide_border=true&card_width=450" />
  <img alt="Most used languages for srnafi" src="https://github-readme-stats.vercel.app/api/top-langs/?username=srnafi&layout=compact&theme=default&hide_border=true&card_width=450" />
</picture>

</div>

---

## Tech Stack

| | |
|---|---|
| **Languages** | C# · C++ · Python · JavaScript / TypeScript · Java · C · Shell · Lua |
| **Backend** | Node.js · Express · Flask · FastAPI · REST APIs · JWT / RBAC |
| **Databases** | MongoDB · PostgreSQL · SQLite |
| **Systems & Desktop** | Win32 API · Direct2D · WebView2 · .NET / WPF · PyQt5 · Electron |
| **Vision / ML tooling** | OpenCV · EasyOCR · OpenVINO |
| **Tools & Frontend** | Git · Docker · Linux · React |

<div align="left">
<img alt="C++" width="44" src="https://skillicons.dev/icons?i=cpp" /> <img alt="C#" width="44" src="https://skillicons.dev/icons?i=cs" /> <img alt=".NET" width="44" src="https://skillicons.dev/icons?i=dotnet" /> <img alt="Python" width="44" src="https://skillicons.dev/icons?i=python" /> <img alt="JavaScript" width="44" src="https://skillicons.dev/icons?i=js" /> <img alt="Node.js" width="44" src="https://skillicons.dev/icons?i=nodejs" /> <img alt="Docker" width="44" src="https://skillicons.dev/icons?i=docker" /> <img alt="Git" width="44" src="https://skillicons.dev/icons?i=git" />
</div>

---

## AI Evaluation Background

- **RWS TrainAI**: 5,000+ multilingual evaluation and annotation tasks (Jan 2025 – Aug 2026)
- **Outlier (Scale AI)**: 400+ assignments in LLM evaluation, adversarial prompting, RLHF and tool-calling, plus reviewing other contributors' work (Oct 2024 – Feb 2026)
- Completed RWS Linguistic AI certification training (machine translation, NMT, LLMs, MT evaluation)

<img alt="footer" width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,100:22D3EE&height=100&section=footer" />
