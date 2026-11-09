# SupiderOS Releases

Public Windows Beta release assets for SupiderOS. This repository contains
installers and release notes only; it does not contain product source code.

## Download

Get the latest Windows Beta installer from the
[Releases](https://github.com/xuanshu-project/supideros-releases/releases) page.
The download is public and does not require an account, invitation or email
registration.

- Current Beta: `1.0.0-beta.2.1-protected.4`
- Platform: Windows x64
- Installer: `SupiderOS-Setup-1.0.0-beta.2.1-protected.4-x64.exe`
- Size: `590,683,648 bytes`
- SHA-256: `994dc6698348006ff81748371ae765a4f0d81302f33396f8bd6c58ce6e368c17`

Verify the file before running it:

```powershell
Get-FileHash .\SupiderOS-Setup-1.0.0-beta.2.1-protected.4-x64.exe -Algorithm SHA256
```

## Beta status and limitations

- This is Beta software for real-world testing. Back up important data and
  expect behavior or data formats to change.
- **The installer is not digitally signed.** Windows SmartScreen or Smart App
  Control may warn about or block it. Do not disable Windows security
  protections. Verify the SHA-256 before running.
- **Clean Windows certification is not complete.** Installation, launch,
  sign-in, uninstall and rollback may fail on some devices. Do not assume every
  Windows PC is compatible.
- Windows 10 version 1903 or later, or Windows 11, x64 only. macOS and Linux
  are not available.
- Requirements: .NET Framework 4.8, Microsoft WebView2 Evergreen Runtime, an
  OpenAI or DeepSeek account for model access, and an internet connection.
- Installation is per-user; administrator rights are not required.

## Feedback

Use [Issues](https://github.com/xuanshu-project/supideros-releases/issues) for
installation problems, Windows security prompts, crashes and product feedback.

**Do not post passwords, API keys, access tokens, personal data or unredacted
logs.** Remove account identifiers, local file paths and secrets before posting.

## Source

SupiderOS product source is not published in this repository. This repository
exists for public binary releases and their release notes only.
