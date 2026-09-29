# My page template

I copy this structure for every new topic, so every page in these notes reads the same way.

## The structure

````markdown
<div align="center">

# NN · Section Title

**Part X — Name** · ✅ Done

</div>

> A short, personal intro: where this fits in my journey and why it matters.

### 📌 What's in here
<!-- a small table linking to each topic on the page -->

## 1. What it is
Plain-English definition. One or two sentences.

## 2. Why it exists
The problem it solves.

## 3. Key points
The core ideas, broken into small labelled chunks, with tables where they help.

## Visual
A diagram — a custom SVG in images/ for the hero, Mermaid for supporting ones.

## ⚠️ Watch out
Bullets of mistakes and misconceptions.

## 🤔 What confused me
The thing that tripped me up, in a quote block, so future-me remembers.

<!-- nav footer: previous · index · next -->
````

## For tool sections (Linux, Docker, Kubernetes, Terraform...)

Concept sections (like 01 and 02) stop at the parts above. Tool sections add:

- **Syntax** — the command shape to remember, in a `code block`.
- **Example** — a real command *with its real output*.
- **🧪 Try it** — a small exercise.

> [!NOTE]
> **About tested output.** Where I can run a tool myself (Linux, Git, Docker, shell, Terraform), the output shown is real. Where a topic needs a cluster or a paid cloud account (Kubernetes, AWS, live CI/CD), I mark the output as **illustrative** and note that I haven't run it on my own machine, rather than pretend it's tested.

## My rules for writing

- Plain English and short sentences, the way I'd explain it to a friend.
- One consistent structure on every page.
- Diagrams render on both GitHub and Notion (Mermaid), with a custom SVG for the hero visual.
- Commands in `code`, the one idea to remember in **bold**.
- Every page ends with **What confused me** — the honest part.
