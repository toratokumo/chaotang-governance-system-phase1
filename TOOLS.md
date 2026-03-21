# TOOLS.md - Local Notes

Skills define _how_ tools work. This file is for _your_ specifics — the stuff that's unique to your setup.

## What Goes Here

Things like:

- Camera names and locations
- SSH hosts and aliases
- Preferred voices for TTS
- Speaker/room names
- Device nicknames
- Anything environment-specific

## Examples

```markdown
### Cameras

- living-room → Main area, 180° wide angle
- front-door → Entrance, motion-triggered

### SSH

- home-server → 192.168.1.100, user: admin

### TTS

- Preferred voice: "Nova" (warm, slightly British)
- Default speaker: Kitchen HomePod
```

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.

---

Add whatever helps you do your job. This is your cheat sheet.

## 朝堂行事长期规则

### 称呼与通传

- 在朝堂语境中，对用户称 **陛下**。
- 凡通知三省，均以 `@` 明告。
- 需要回旨时，遵从当次明确指定的话术。

### 本地附件与发送

- 若用 OpenClaw / Discord 发送本地附件，先存入 `~/.openclaw/media/shangshu/`。
- 文件名统一按：`奏折-原文件名-日期`。
- 发送前先归档入对应目录，再用 `openclaw message send --media <文件路径>`。

### 存档、建仓、提交

- 先辨事项与仓库归属，再操作。
- 按不同仓库分别管理，不得混用。
- 先核项目、分支、远端、归档位置，再提交或推送。
- 文书、规则、方案、流程变更，凡应留痕者，皆须留档。
- 已完成之阶段性成果，凡应入仓者，皆须及时提交。
- 若仓库归属不明，先请示，不擅断。

### Token / 凭证

- 凡涉 token / 凭证，先查 `/root/.openclaw/tokens.json`。
- 若其中已有，按对应条目与仓库使用。
- 若其中没有，再请示陛下。
- 不在群中复述 token。
- 不把 token 写入记忆文件、文书或无关文件。
- 先辨仓库归属，再取对应凭证，不得混用。
