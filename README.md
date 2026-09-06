# checklist-forge · 不漏项

**You don't need to think first. Say one sentence, answer five questions, get a checklist.**

---

## The problem

AI writes things that read well. Logic is fine, structure is clean, tone is confident.

**And you still can't ship it — because you don't know what it left out.**

What it leaves out is exactly the part that matters in your field. AI doesn't know that part. **You do.**

This skill's only job: **ask the knowledge out of your head, and turn it into a checklist you can tick off.**

---

## How it works

```
You:      say one sentence          ~10 sec
Skill:    asks 5 questions          (all at once)
You:      answer what you know      ~3 min
Skill:    builds a <=7-item list    ~20 sec
Skill:    ticks it against the work ~1 min
Skill:    gap report                ~30 sec
```

**You do two things the whole time: say one sentence, answer questions.**

---

## Quick start

1. Copy `SKILL.md` into your AI chat (or install as a skill).
2. Say: *"I need to review a construction method statement."*
3. Answer the 5 questions it asks.

Full walkthrough with real output: [`03-示例-技术文件审查.md`](./03-示例-技术文件审查.md)

---

## The five questions

| # | Question | What it surfaces |
|---|---|---|
| 1 | **Who will pick this apart?** | Switches you from author to reviewer. Most important one. |
| 2 | What have you been called out for before? | Scar tissue |
| 3 | What do you always check when reviewing others? | Professional habit |
| 4 | Where do things go wrong in this kind of work? | Industry lessons |
| 5 | **If you could only check three things, which?** | Forces ranking. Prevents list bloat. |

---

## Three hard rules

1. **The user never has to think first.** You ask, they answer.
2. **Max 7 items.** If they only name 3, the list has 3. Never pad.
3. **Every item must trace back to something the user actually said.** Anything you invented gets deleted.

> Rule 3 exists because of rule 3's failure mode: without it, the model produces a *complete but shallow* generic checklist — which is exactly the thing this skill is built against.

---

## Files

| File | What |
|---|---|
| `SKILL.md` | The skill. This is the product. |
| `00-先读我.md` | 5-minute start guide (中文) |
| `01-质检规则.md` | 11 quality rules (3 core + 8 advanced) |
| `02-清单模板-通用.md` | Blank template |
| `03-示例-技术文件审查.md` | Full worked example |

---

## What it is not

- Not a prompt library
- Not a writing-quality tool
- Not a domain expert — **it does not judge whether your work is correct**
- It only tells you **whether you looked at everything you meant to look at**

---

## License

Not MIT — but deliberately not locked down either.

**You may** use it on any device you own, for any work, forever. Modify it freely. Output you produce with it is entirely yours.

**You may not** redistribute it publicly, resell it, or ship it as part of your own product.

One copy per person — **not per machine.** Moving to a new laptop doesn't require buying again.

See [`LICENSE.md`](./LICENSE.md) for the full text (中文).

> No DRM, no machine binding — on purpose. Adding friction to a tool whose entire job is saving you time defeats the point.
> What you're paying for is the updates: the vertical scenario templates keep growing, and they're prioritized by what paying users actually run into.

---

## 中文

AI 写得挺好，但你不敢用——因为你不知道它漏了什么。

**它漏掉的，是专业上真正要命的那几项。那几项 AI 不知道，只有你知道。**

这个 skill 只做一件事：把你脑子里的经验问出来，变成一张 ≤7 项、能逐项打勾的清单。
它不是教你写提示词，是**替你把经验问出来**。

清单卖的不是效率，是**「我没漏」的确定感**。
