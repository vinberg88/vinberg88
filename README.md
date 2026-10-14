<div align="center">

# 🐧 VINBERG LINUX LAB

### Full Linux desktops on Windows

**Practical WSL builds, complete desktop experiments, launchers and diagnostics — built and tested in Stockholm.**

<img src="https://img.shields.io/badge/Windows_11-WSL_2-0078D4?style=for-the-badge&logo=windows11&logoColor=white" alt="Windows 11 and WSL 2" />
<img src="https://img.shields.io/badge/Linux-Desktop_Lab-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux Desktop Lab" />
<img src="https://img.shields.io/badge/Stockholm-Sweden-006AA7?style=for-the-badge" alt="Stockholm, Sweden" />
<img src="https://img.shields.io/badge/2026-CODE_IS_LIFE-6C5CE7?style=for-the-badge" alt="Code is life" />

<br /><br />

> **Pick a distro. Launch a desktop. Break the boundary.**

[Featured builds](#-featured-builds) · [Desktop gallery](#-desktop-gallery) · [All Linux projects](#-pick-your-linux) · [About Mattias](#-about-mattias)

</div>

---

## 👋 Welcome to the lab

I am **Mattias Vinberg**, a tech consultant and software builder from Stockholm, Sweden.

This is my Linux-on-Windows workshop: reproducible WSL distributions, real desktop sessions, practical installers and experiments that go beyond a terminal prompt. I like projects that can be installed, started, diagnosed and used for real.

What you will find here:

- complete Linux desktop experiments for WSL 2
- clean installation guides and repeatable launchers
- health checks, logs and recovery commands
- screenshots and videos from actual setups
- honest notes about what is tested, experimental or still coming next

## 🚀 Featured builds

| Project | Experience | Display path | Project status |
| :--- | :--- | :--- | :--- |
| **[Fedora Linux on WSL](https://github.com/vinberg88/fedora)** | Fedora 44 with KDE Plasma 6 and a managed <code>kde6-x410</code> launcher | X410/X11 with WSLg audio | Desktop startup confirmed on my setup |
| **[Ubuntu 26.04 Budgie](https://github.com/vinberg88/ubuntu26.04-wsl2-budgie)** | Budgie 10.10 with start, stop, restart, sizing and diagnostics | WSLg; X410 is not required | Managed desktop launcher |
| **[openEuler Desktop Collection](https://github.com/vinberg88/openEuler)** | Kiran, GNOME and a growing desktop collection for openEuler | Kiran tested through X410 | Community desktop project |
| **[EndeavourOS for WSL](https://github.com/vinberg88/EndeavourOS)** | Arch-based WSL package with a KDE Plasma 6 guide | WSL 2 desktop experiment | Community build and releases |
| **[Pop!_OS 24.04 WSL Base](https://github.com/vinberg88/pop-os-wsl)** | Clean systemd-enabled base with OOBE and <code>pop-wsl doctor</code> | WSLg-ready base | Release 0.1.1 |

## 🖥️ Desktop gallery

<table>
  <tr>
    <td width="50%" align="center">
      <a href="https://github.com/vinberg88/fedora">
        <img src="https://github.com/user-attachments/assets/14f4c7d6-95ea-4865-9d81-c83963399f5e" alt="Fedora 44 with KDE Plasma 6 running through WSL" width="100%" />
      </a>
      <br />
      <strong>Fedora 44 + KDE Plasma 6</strong><br />
      A full X11 desktop with launcher, diagnostics and a Windows shortcut.
    </td>
    <td width="50%" align="center">
      <a href="https://github.com/vinberg88/EndeavourOS">
        <img src="https://github.com/user-attachments/assets/3c31e798-1325-4f64-9aef-f44e0645a00b" alt="EndeavourOS with KDE Plasma 6 running through WSL" width="100%" />
      </a>
      <br />
      <strong>EndeavourOS + KDE Plasma 6</strong><br />
      An Arch-based WSL journey with a complete desktop guide.
    </td>
  </tr>
</table>

## 🧪 How I validate a WSL project

A process staying alive is not enough. The useful question is whether the result can actually be installed and used.

<div align="center">

**Clean install** → **First-run setup** → **systemd** → **Package test** → **Doctor command** → **Visible desktop** → **Cold restart**

</div>

Each repository documents its own scope and requirements. Some desktop experiments use WSLg, while others use X11 and X410. Projects that depend on third-party software say so directly.

## 🌌 Pick your Linux

| Debian family | Arch family | RPM and enterprise family |
| :--- | :--- | :--- |
| [Ubuntu](https://github.com/vinberg88/ubuntu) | [Arch Linux](https://github.com/vinberg88/arch) | [Fedora](https://github.com/vinberg88/fedora) |
| [Ubuntu 26.04 Budgie](https://github.com/vinberg88/ubuntu26.04-wsl2-budgie) | [EndeavourOS](https://github.com/vinberg88/EndeavourOS) | [openEuler](https://github.com/vinberg88/openEuler) |
| [Debian](https://github.com/vinberg88/debian) | [CachyOS](https://github.com/vinberg88/cachyos) | [AlmaLinux](https://github.com/vinberg88/almalinux) |
| [Pop!_OS](https://github.com/vinberg88/pop-os-wsl) | [Manjaro](https://github.com/vinberg88/manjaro) | [Red Hat](https://github.com/vinberg88/redhat) |
| [ParrotOS](https://github.com/vinberg88/ParrotOS) | [Alpine](https://github.com/vinberg88/alpine) | [CentOS](https://github.com/vinberg88/centos) |
|  |  | [openSUSE](https://github.com/vinberg88/opensuse) · [SUSE](https://github.com/vinberg88/suse) |

## 🌉 Next major project: WayBridge

**WayBridge** is the next step: one polished Windows application for setting up, launching and managing Linux desktop sessions on WSL.

The direction is simple:

- one real Windows application
- clear first-run setup
- Start, Stop and Restart controls
- useful diagnostics and recovery
- accessibility and documentation
- Windows/MSIX packaging with Microsoft Store-quality finish

The goal is not just to start a desktop. The goal is to make the complete experience feel reliable and finished.

## 🛠️ Beyond WSL

I also build Windows, Android and web projects:

- **[Blanket for Android](https://github.com/vinberg88/blanket-android)** — relaxing ambient sounds for Android
- **[TubeDesk for Windows](https://github.com/vinberg88/youtube-desktop-win)** — a desktop YouTube experience
- **[WSL information site](https://vinberg88.github.io)** — guides and project links
- **[YouTube](https://www.youtube.com/@mattiasvinberg)** — Linux and WSL walkthroughs

## 👨‍💻 About Mattias

I work at the intersection of software engineering, architecture, DevOps, delivery leadership and practical AI adoption. I enjoy taking an idea all the way to a working result — with clear documentation, repeatable setup and enough diagnostics to understand what happens when something goes wrong.

My working principles:

- **Outcome first** — build something people can actually use
- **Pragmatic engineering** — balance speed, quality and maintainability
- **Visible proof** — test the real interface, not only the process
- **Honest status** — separate verified results from experiments and roadmaps
- **Keep learning** — Linux, Windows and open source are more fun when boundaries are crossed =)

## 🤝 Connect

[![GitHub](https://img.shields.io/badge/GitHub-vinberg88-181717?style=for-the-badge&logo=github)](https://github.com/vinberg88)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mattias_Vinberg-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mattias-vinberg/)
[![YouTube](https://img.shields.io/badge/YouTube-Mattias_Vinberg-FF0000?style=for-the-badge&logo=youtube)](https://www.youtube.com/@mattiasvinberg)
[![Bluesky](https://img.shields.io/badge/Bluesky-mattiasvinberg-0285FF?style=for-the-badge&logo=bluesky)](https://bsky.app/profile/mattiasvinberg.bsky.social)

📧 **mattias@vinberg.pm**

---

> These are personal/community projects unless a repository explicitly states otherwise. Linux distribution names, desktop names and product trademarks belong to their respective owners.

<div align="center">

### CODE IS LIFE — BUILD, TEST, LEARN, REPEAT 🐧

</div>
