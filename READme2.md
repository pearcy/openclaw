# 🦞 OpenClaw — Personal AI Assistant

```bash

VS Code:
- pnpm openclaw gateway start
- pnpm openclaw gateway stop
- pnpm openclaw gateway status
- pnpm openclaw devices list
- pnpm openclaw configure

Terminal:

Terminal:
- pnpm openclaw tui        # opens the terminal UI
- pnpm openclaw web         # opens chat in your browser


```

First, get rid of the changes you don't care about:

```bash
git checkout -- README.md pnpm-lock.yaml
```

Then commit and push your notes file:

```bash
git add READme2.md
git commit --no-verify -m "Add personal notes file"
git push fork main
```

**Going forward, your workflow is:**

When you update `READme2.md`:

```bash
git add READme2.md
git commit --no-verify -m "Update notes"
git push fork main
```

When you want the latest from the community:

```bash
git pull original main
git push fork main
```

That's it — two flows, both short.

*** Daily Notes ****

4.3.26 @ 10:34 AM
code4/openclaw
branch: main

-- test OpenClaw on it’s ability to replace me as go between Architect and Contractor
— control the back and forth with Claude
