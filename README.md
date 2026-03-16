# Playwright Skills Lab

A small Playwright Test project used for experimenting with browser automation and the `playwright-cli` agent skill.

> This repo is organized as a test playground. It includes a minimal Playwright Test setup, an example spec, and an agent skill definition under `.agents/` for using the `playwright-cli` tool.


## ✅ Prerequisites

[![NodeJs](https://img.shields.io/badge/-NodeJS-%23339933?logo=npm)](https://nodejs.org/en/download/)
[![VSCode](https://img.shields.io/badge/-Visual%20Studio%20Code-%233178C6?logo=visual-studio-code)](https://code.visualstudio.com/download)



## 🚀 Quick Start

```bash
# 1) Install dependencies
npm install

# 2) Install Playwright browsers
npx playwright install
```

## 🧰 Common Commands

| Task | Command |
|------|---------|
| Install deps | `npm install` |
| Install Playwright browsers | `npx playwright install` |
| Run all tests | `npx playwright test` |
| Run tests in one browser | `npx playwright test --project=chromium` |
| Show HTML report | `npx playwright show-report` |


## 🧩 Project Structure

- `playwright.config.ts` - Playwright Test configuration (browsers, retries, reporter, etc.)
- `tests/` - Contains Playwright test specs (example: `example.spec.ts`)
- `.agents/` - Agent skill definitions (e.g., `playwright-cli` skill)
- `skills-lock.json` - Locked skill versions for consistent behavior across machines


## 🤖 Agent Skill: `playwright-cli`

This repo includes a skill manifest for the `playwright-cli` tool in `.agents/skills/playwright-cli/SKILL.md`.

The skill enables an agent to drive browser automation via the `playwright-cli` command-line tool. It is not required for running Playwright tests, but it is used when running the agent workflows.


## 📚 Resources

- Playwright Test docs: https://playwright.dev/docs/intro
- Playwright CLI docs: https://github.com/microsoft/playwright-cli
