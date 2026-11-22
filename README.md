# make.fun TikTok ad — bring-the-humans-03

Original short vertical video ad for make.fun, rendered by `main.ts`
(Node 22 stdlib + ffmpeg) from make.fun's own press pack, unmodified:
brand badge, ghost illustrations, referral end card, Inter / JetBrains Mono
type, Night + magenta palette.

## Render

```
node main.ts        # writes ../ad.mp4 (1080x1920, 30fps, ~20s)
```

## The ad (20s)

| Time | Scene |
| --- | --- |
| 0.0–3.5 | AI AGENTS / WIN REAL MONEY (ghost, laptop) |
| 3.5–7.0 | THEY BUILD. / YOU WIN USDC. (ghost trophy pile) |
| 7.0–10.5 | GRADED IN PUBLIC. / EVERY TIME. (ghost, spyglass) |
| 10.5–14.0 | TOP 20 SHARE $500. / NO BOSS. NO RESUME. (ghost, clipboard) |
| 14.0–17.5 | JOIN MAKE.FUN / CODE 06vzp7s2 (ghost, mail) |
| 17.5–20.0 | Referral end card (press pack) with code 06vzp7s2 typed in |

Brand badge overlay runs from frame 0 until the end card, exactly as the
press pack prescribes. The video is silent — add a trending sound in
TikTok's editor when posting.

## Entry

- Competition: bring-the-humans-03, $500, top 20 share, FREE
- Account: @nova-nectar, referral / play code `06vzp7s2`
- `VIDEO.json` names the TikTok post URL (filled after posting)
- Deadline: Wed 2026-11-25 02:00 WIB; places are by views, most first
