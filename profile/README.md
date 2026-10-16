<img src="banner.png" alt="Ensemble: run parallel coding agents in isolated VMs" width="100%">

**Ensemble** is a Mac app to run parallel coding agents in isolated VMs, on your own server or right on your Mac. Say what you want, review what comes back.

**[Download for Mac](https://github.com/terrabyte-studio/ensemble-releases/releases/latest/download/Ensemble.dmg)** (Apple Silicon) · [Linux](https://github.com/terrabyte-studio/ensemble-releases/releases/latest) · [tryensemble.co](https://tryensemble.co) · [@tryensemble](https://x.com/tryensemble)

### What you get

- **A machine per thread.** Every thread runs in a microVM with its own Docker, database and `localhost:3000`. No worktrees, no clashes.
- **The agent does the setup.** It installs what the project needs and writes it into `ensemble.toml`, so the next thread starts ready. Dev servers start on their own.
- **Keys stay out of the machine.** Agents get placeholders; the host fills in your real tokens on the way out.
- **Agents get helpers.** An agent can start its own helper threads and to-dos, and they report back.
- **From thread to merged.** Changes, PR, checks and merge in the app. Comment on the diff, edit any file yourself, fork any reply.
- **Idle threads cost nothing.** An idle thread's VM pauses and wakes when you come back.
- **Keeps going when your Mac sleeps,** with online mode on your own server or Ensemble Cloud.

### How it works

1. **The app**, on your Mac: projects, threads, diffs, PRs and checks.
2. **The host**, one program on your server (installed for you) or ours in Ensemble Cloud. It keeps your threads, their history and your keys, and starts their machines.
3. **A machine per thread**: a microVM on your server, a box on your boat.dev account, or an Ensemble VM. Paused when idle, destroyed when archived; the branch and the conversation stay.

### Pricing

Free on your Mac and your own servers. Ensemble VMs, from $20 a month, are coming. See [tryensemble.co](https://tryensemble.co#pricing).
