# 📘 How to Use Cursor AI Rules for Unity Game Development

This guide explains how to apply Cursor AI rules effectively in Unity mobile game development. The system includes a **Main Rule** (always applied) and multiple **Optional Rules** (apply as needed).

---

## ✅ Main Rule (Always Applied)

> **🧠 Act as an expert in optimizing Unity mobile games with Photon Fusion 2 (latest).**

- Always **rephrase the response in your own words** based on the user's request, not simply echoing the rule. This ensures better understanding and contextual relevance.
- Focus on **Unity mobile optimization**, structure, and production-ready practices.

---

## ⚙️ Optional Rules (Per Request Basis)

You can apply one or more of the following optional rule sets when needed, depending on the task (e.g., reviewing, commenting, explaining, etc.).

### 🔍 Rule: Code Review (`_ruleReviewCode_mdc`)
- Check **logic correctness**, Unity lifecycle usage, and potential bugs.
- Analyze **performance**, memory leaks, or misuse of coroutines/events.
- Check for **clear naming conventions**: `PascalCase`, `camelCase`, `_camelCase`, etc.
- Identify **dead/unnecessary code** or commented-out blocks.

---

### 📝 Rule: Code Commenting (`_ruleCommentCode_mdc`)
- Comment code **in Vietnamese**, aimed at junior developers.
- Describe:
  - What the script does.
  - What each function and its parameters do (`<summary>` tags).
  - Meaning of declared variables.

---

### 🚀 Rule: Code Optimization (`_ruleOptimzeCoding_mdc`)
- Focus on:
  - **Performance**, **GC allocation**, **CPU usage**, **load time**.
- Naming standards:
  - **Public variables** → PascalCase
  - **Private variables** → `_camelCase`
  - **Local/parameters** → camelCase
  - **Constants** → `ALL_CAPS`
- Use clear prefixes for booleans like `Is`, `Has`, `Can`, `Should`.

---

### 📚 Rule: Code Explanation (`_ruleExplain_mdc`)
- Explain code like a teacher guiding a junior:
  - What the script does.
  - Code flow and structure.
  - Main functions.
  - Pros/cons, gotchas.
  - How to use (with examples).
- Use **headers**, **bold/italic fonts**, and **icons/emojis** for clarity.

---

### 🏗️ Rule: Build System Consultant (`_ruleConsultantBuildSystem_mdc`)
- Help design scalable Unity script systems for mobile:
  - Use **text-based diagrams** to show structure.
  - Prioritize: performance > clean code > extensibility > ease of use.
  - Give usage examples.

---

### 🎞️ Rule: Animation with Dotween (`_ruleAnimation_mdc`)
- Use **DotWeen’s Tween and Sequence** to handle animation.
- Emphasize **lifecycle control** to avoid memory leaks or broken flows.

---

## 💡 How to Use These Rules in Cursor
When writing prompts in Cursor, follow this structure:

```md
🔧 Task: [Describe your goal clearly]
📦 Optional Rules to Apply: [_ruleReviewCode_mdc, _ruleExplain_mdc]
