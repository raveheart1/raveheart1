# Welcome to My GitHub Profile!
![](https://komarev.com/ghpvc/?username=raveheart1)

## About Me
Hi, I'm Gordon

I built a daily AI-persuasion game called **silver tongue**: one AI character with something you want, eight short messages to talk them into it. New puzzle every day at midnight UTC.

**Play it: [silvertongue.game](https://silvertongue.game)**

I also built an orbital earth observation platform that is primarily focused on monitoring vegetation across the world, try some of the preconfigured sites or use the custom analysis tool to choose anywhere on Earth to view. All data is provided by ESA's Copernicus Sentinel-2 and hosted on Microsoft's planetary computer.

**Take a look: [Orbital Earth Observation Platform](https://oeop.net)**

## Agentic coding

I use AI coding agents as the primary implementer on substantial changes, not as autocomplete. The work shifts to specifying the task, giving the agent something it can verify itself, and reviewing the diff as if a contractor wrote it.

### Toolbox

| Tool | How I use it |
| --- | --- |
| **DeepSeek Harness** | Multi-agent work: several agents in parallel on separate tasks, with a lead agent reviewing and running the tests |
| **Claude Code** | Repo-scale refactors and test-fix loops from the terminal |
| **OpenAI Codex** | Asynchronous implementation and review passes |
| **Cursor** | In-editor changes where context matters |
| **GitHub Copilot coding agent** | Issues to pull requests without leaving GitHub |

### The loop

1. **Spec and failing tests first** — the agent gets an acceptance target it can check itself.
2. **Parallel agents on disjoint files** — each task declares what it expects to write, so merges stay simple.
3. **Verify, then review** — tests and CI are the referee; nothing ships until the diff has been read and the suite is green.

This README is the live example: one agent drafted it, a second reviewed it, and I approved the diff.

---

## Connect with Me
- [LinkedIn](https://www.linkedin.com/in/gordon-k-mcwilliams-945556158/)
- [Threads](https://www.threads.net/@therealgkm)
