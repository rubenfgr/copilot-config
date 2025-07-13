
# Copilot Config

> [!TIP]
> **Supercharge your GitHub Copilot with reusable instructions, prompts, and chatmodes for consistent, team-aligned AI assistance.**

## Overview

**Copilot Config** is a curated collection of custom instructions, prompts, and chatmodes to tailor GitHub Copilot Chat for your team's workflows, coding standards, and project requirements. It enables you to:

- Enforce best practices and coding guidelines
- Share reusable prompts for common tasks
- Define agent behaviors for specific roles or stacks
- Achieve consistent, context-aware AI assistance across your projects

## Features

- 📋 **Custom Instructions:** Repository-wide rules for code generation, reviews, and more
- 🎯 **Reusable Prompts:** Task-specific, shareable prompt files
- 🧩 **Custom Chatmodes:** Role-based agent behaviors and tool configurations
- 🛠️ **Extensible:** Add your own instructions, prompts, and chatmodes

## Quick Start

1. **Browse the `.copilot/` directory:**
   - `instructions/` — Coding standards and best practices for various stacks
   - `prompts/` — Reusable prompt files for common tasks
   - `chatmodes/` — Custom agent modes for Copilot Chat
2. **Install or activate files in VS Code Copilot Chat** as needed
3. **Contribute your own!** See [CONTRIBUTING.md](awesome-copilot/CONTRIBUTING.md)

## Example: TanStack Start + Shadcn/ui

> [!NOTE]
> See `.copilot/instructions/tanstack-start-shadcn-tailwind.instructions.md` for best practices on TanStack Start, Shadcn/ui, Tailwind, Zod, and TanStack Query.

## Directory Structure

```text
.copilot/
  instructions/   # Coding standards and best practices
  prompts/        # Reusable prompt files
  chatmodes/      # Custom agent modes
awesome-copilot/
  chatmodes/      # Community chatmodes
  instructions/   # Community instructions
  prompts/        # Community prompts
```

## Why Use Copilot Config?

> [!IMPORTANT]
> **Consistent, context-aware AI**: Ensure Copilot Chat always follows your team's standards, no matter the project or developer.

---
For more, explore the `.copilot/` and `awesome-copilot/` folders, or open an issue to suggest improvements!
