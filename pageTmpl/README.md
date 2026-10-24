# Pane Studio Workspace — Split-Screen File Manager for Windows

![version](https://img.shields.io/badge/version-${version}-blue)
![size](https://img.shields.io/badge/size-8.5MB-blue)
![license](https://img.shields.io/badge/license-free-green)
![platform](https://img.shields.io/badge/platform-Windows%2010%2F11%20x64-0078D6)

Taskbar packed to the brim, three pages of Alt+Tab just to find the window you were using — and that Snap layout you arranged? Gone after every reboot. Pane Studio Workspace takes the direct approach: **instead of jumping between a pile of windows, put them together in one.** Pack four kinds of panes — file manager, web browser, document viewer, and terminal — into a single window with as many panes as you need: any pane can be split horizontally or vertically, maximized, and restored, and **every pane can hold multiple tabs** (drag to reorder, move between panes, or Ctrl-drag to duplicate). A layout you arrange can be named and saved as a **workspace**; clicking its workspace tab brings the whole group back, and it survives a reboot unchanged.

![Pane Studio Workspace main window overview](screenshots/img1.png)

*One window, four workspaces — folders, web pages, documents, and spreadsheets, each in its place, with multiple tabs in every pane. A single taskbar icon.*

## Download

- **Windows 10 / 11 (64-bit)** — free · no ads · no bundling · no account needed · runs locally and uploads nothing; installer approx. 8.5 MB:
  [⬇️Download PaneStudioWorkspace](https://raw.githubusercontent.com/xlan8/paneStudioRelease/refs/heads/main/${download_file_name})
- Install takes about 10 seconds. If Windows shows a blue warning (common for unsigned new apps), click **More info → Run anyway**.
- The app has a built-in auto-updater: when a new version is released, you'll be prompted at startup and can upgrade with one click.
- UI languages: Simplified Chinese, Traditional Chinese, English, Japanese, German, Spanish, French (selected automatically based on the system language).
- Web panes are based on Microsoft Edge WebView2, which Windows 10/11 usually includes out of the box.

## The 30-Second Tour

1. **Download and install** — about 10 seconds, no account needed;
2. **Drag in and get to work** — folders, web pages, documents, and the terminal: drag them into any pane and split however you like; every pane takes multiple tabs, so one cell can hold a whole set of related tools;
3. **Save it as a workspace** — name your layout; tomorrow, one click on its workspace tab brings the whole group back.

## Why You Need It

| Before: five or six windows piled up on your desktop | After: one click on a workspace tab brings the whole layout back |
| :-: | :-: |
| ![Before: five or six windows piled up on the desktop](screenshots/img10_0.png) | ![After: one window with folders, web pages, documents, and terminal each in their place; every pane can hold multiple tabs](screenshots/img1_0.png) |

Editing a spreadsheet while reading a document, looking something up in a browser, and running a few commands — the result is four or five windows juggled back and forth: hunting for them, minimizing them, covering each other up.

- The taskbar is packed, and you flip through **three pages of Alt+Tab** just to find the window you were using;
- Windows 11 Snap is only a temporary arrangement — **no name, no saving, everything resets after a reboot**;
- First task of every workday: put back the windows you closed yesterday, **one by one**;
- In a remote desktop session, local files have to go through a network drive or shared folder before they reach the remote PC.

Pane Studio Workspace takes the direct approach: **instead of jumping between a pile of windows, put them together in one** — all panes live in a single window, so the taskbar keeps a single icon; every pane can hold several tabs, so one cell covers a whole set of folders, terminals, or web pages; arrange a layout, give it a name, and save it as a **workspace** — one click on its workspace tab brings the whole group back, unchanged even after a reboot.

## Five Pane Types — Combine Freely, Open Any Number

The main interface has two parts: a **workspace bar** on the left (each tab is an independent window layout) and an arrangement of **panes** on the right. Each pane can be:

| Pane type | Description |
| --- | --- |
| **Folder** | Uses the real Windows Explorer control — native system icons, thumbnails, sorting, and the full right-click menu, with SVN, Git, and every other shell extension intact. Not an imitation list |
| **Web** | An embedded browser (WebView2) with address bar, back/forward, and refresh; each web tab can enable **sandbox mode** independently, keeping login state isolated from other tabs and panes so multiple accounts never mix |
| **Document Viewer** | A built-in PDF reader that also opens Markdown and Word — drag in a file, with search and zoom; Excel workbooks (.xlsx) can be viewed, edited, and saved back to the original file |
| **PowerShell** | An embedded terminal that runs commands right in the pane; can be set to run a fixed command automatically at startup |
| **Blank** | An empty pane with no type yet — click an icon to switch it to any of the above |

Any pane can be **split horizontally** or **split vertically**, and can be **maximized** to fill the whole workspace and then restored; split ratios are remembered.

Every pane can also hold multiple **tabs**: keep several folders, terminals, web pages, or document previews in one pane and switch instantly. Drag tabs to reorder them, drop them into another pane, hold Ctrl while dragging to duplicate, or middle-click to close. After a restart or workspace switch, each pane reopens on the tab you were last viewing.

![Four pane types on one screen](screenshots/img2.png)

*Folder, browser, document, and terminal — side by side, never covering each other.*

## Feature Overview

- **Have TortoiseSVN installed? Commit and browse logs right inside the pane** — the folder pane embeds Windows' own Explorer control, so a right-click opens the genuine system context menu with every shell extension intact: update, commit, and browse logs with TortoiseSVN; open Git Bash, pull, and push with Git; compress or extract archives, scan for viruses, open with another app — anything Explorer can do on right-click works here identically. Icons, thumbnails, sorting, and zooming are native system behavior too, plus instant keyword filtering and multiple zoom levels.

![Native folder view and context menu](screenshots/img3.png)

*With TortoiseSVN installed, update, commit, and browse logs right inside the pane.*

- **Read the spec on top, edit the spreadsheet below — all in one window** — PDF, Markdown, and Word all support search and zoom as read-only previews; Excel workbooks (.xlsx) can be edited directly and saved back to the original file.

![Document viewing and direct Excel editing](screenshots/img4.png)

- **Per-tab sandbox — multiple accounts never mix** — open web pages without leaving the workspace; each web tab can enable **sandbox mode** independently, keeping login state isolated from other tabs and panes.

![Web pane sandbox mode](screenshots/img5.png)

- **Move files straight between panes** — copy / cut / paste directly between panes; pasting runs in a separate progress window showing real-time progress that can be cancelled at any time, so long tasks never freeze the UI.

![Paste progress window, cancellable at any time](screenshots/img6.png)

- **Save your layout as a workspace — tomorrow it's one workspace-tab click away** — create as many workspaces as you like, each with its own layout; rename, color-tag, drag to reorder, and delete, so layouts can be reused long-term.
- **Readable Markdown out of the box** — headings, tables, code blocks, and images fully rendered.

![Markdown reading and workspace context menu](screenshots/img7.png)

- **A real-world task: a Microsoft Store submission in three panes** — the screenshot above is the actual layout used when submitting the app to the Microsoft Store: **top-left** is a folder pane holding the screenshots to upload; **bottom-left** is a web pane open on the Store submission page; the **right** side is a document pane showing the submission checklist as Markdown. Screenshots are dragged straight from the folder pane into the upload area of the web page, following the checklist as you fill in the form — **all without ever leaving this one window**, one window for the whole process.

![Three-pane layout during a Microsoft Store submission: screenshots folder top-left, Store submission page bottom-left, submission checklist Markdown on the right](screenshots/img8.png)

*Follow the checklist as you fill in the form — never leaving the window.*

- **Side by side with your other apps: assets on the left, design on the right** — Pane Studio Workspace isn't meant to replace the software you already use — it gives it a better place on screen. On the **left** is Pane Studio Workspace, with a folder pane holding the art assets for the job at hand — icons, slices, and reference images, filed by project. On the **right**, side by side, is Photoshop, with a UI mockup in progress. Assets are always within reach: drag a file straight out of the pane into Photoshop, or copy and paste between the two windows — no more Alt+Tab ping-pong between Explorer and PS. Save in Photoshop and the folder pane on the left **refreshes instantly**, so newly exported slices and updated images appear in the list right away. And **with a second monitor it gets even better: Pane Studio Workspace on one screen, Photoshop on the other**, so each app gets a full screen of its own.

![Pane Studio Workspace side by side with Photoshop: on the left, Pane Studio Workspace's folder pane shows the art assets of a UI project; on the right, Photoshop is being used to design the interface](screenshots/img9.png)

*Save in Photoshop — the folder pane on the left refreshes instantly.*

- **Multiple tabs per pane** — every pane holds several tabs; drag to reorder, drop into another pane, hold Ctrl to duplicate, or middle-click to close.
- **Built-in terminal** — the PowerShell pane runs commands directly in a specified directory; supports running a fixed command automatically at startup.
- **AI automation support** — enable "Agent support" in Settings and the app reserves a local debug port, letting external AI tools (e.g. Playwright) take over web panes for automation; turn it off whenever you're done.
- **File change watching** — folder contents refresh automatically when modified externally, no need to press F5.
- **Dark mode & light mode** — switches automatically with your Windows system setting.
- **Always on top** — pin the window above everything with one click.
- **7 UI languages** — Simplified Chinese, Traditional Chinese, English, Japanese, German, Spanish, French, selected automatically based on the system language.

## Who It's For

- **If you always have a pile of folders, documents, spreadsheets, and terminals open** — a folder to look something up, a spreadsheet to edit, a terminal to run commands; the windows pile up until Alt+Tab takes pages. Lay them out in one window, each in its own pane and out of each other's way, and the taskbar keeps a single icon.
- **If you design games** — save one workspace per system: the equipment tables and design docs as one, the character system's as another. Lay out once, reuse forever, switch with one click.
- **If you're a developer** — source directory on the left, terminal on the right, a browser pane for error lookups. Save the layout as a workspace; tomorrow it's one workspace-tab click away.
- **If you design** — asset library on the left, Photoshop on the right, instant refresh on save — no more Alt+Tab ping-pong between Explorer and PS.
- **If you just want a quick look at a PDF / Word / Excel** — drag it into a pane; close the window when done and leave no pile of leftover windows.
- **If you work over remote desktop** — files in a remote clipboard paste directly into a pane — no more manual uploading and downloading.

## FAQ

- **How is it free?** — Completely free for now; the product comes first. No ads, no bundling, no account needed.
- **Will my files be uploaded?** — No. Pane Studio Workspace runs locally and doesn't collect file contents (see the [Privacy Policy](privacy.html)).
- **How is this different from Clover / QTTabBar / Q-Dir / Files?** — The folder pane is the real Windows Explorer control with every shell extension intact — and it doesn't stop at files: terminal, web, and documents share the screen, every pane can hold multiple tabs, and layouts are saved as workspaces.
- **What does Excel editing cover?** — change values, add records, edit most formulas, and adjust common formatting, all saved back to the original file; a few items (such as images, charts, macros) aren't supported yet, and the app tells you before the first save (see Things to Know).

## Things to Know

- **Requires Microsoft Edge WebView2 Runtime** — Windows 10/11 usually includes it; if a web pane says it can't initialize, install the runtime from Microsoft's website.
- **What Excel editing covers** — the built-in spreadsheet editor covers everyday edits: change values, add records, edit most formulas, and adjust common formatting, saved back to the original file. A few documents may contain content that isn't supported yet (such as images, charts, macros), which can be lost on save — the app asks you to confirm before the first save, so please back up important files.
- **Local debug port** — "Agent support" in Settings is off by default. When enabled, the app reserves a local debug port so AI tools on the same machine can drive web panes; it is not reachable from outside your PC and uploads nothing. If your firewall prompts you, allowing local access is fine.

## App Information

| Item | Details |
| --- | --- |
| Name | Pane Studio Workspace |
| Current version | ${version} |
| Size | approx. 8.5 MB (installer) |
| Category | System Tools → File Management / Multi-pane Workspace |
| License | Free |
| Supported OS | Windows 10 / 11 (64-bit) |
| UI languages | Simplified Chinese, Traditional Chinese, English, Japanese, German, Spanish, French |
| Required component | Microsoft Edge WebView2 Runtime |
| Installer formats | NSIS (.exe), MSI |

## Contact

Questions, feedback, or bug reports — reach us on any of these:

- **Email**: <w13683434020@gmail.com>

---

© 2026 Pane Studio Workspace. All rights reserved. For Windows 10 / 11 (64-bit) · [Privacy Policy](privacy.html)
