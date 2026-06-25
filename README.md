<h1 align="center">Sheraz Aurang Zaib</h1>

<p align="center">
  <b>Full-Stack Software Engineer — Ruby on Rails + TypeScript</b><br>
  I build developer tools and ship full-stack products end to end: backend, frontend, and deploy.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sherazp995"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:sherazp995@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Lahore,%20PK-open%20to%20remote-2ea44f?style=flat" alt="Location">
</p>

---

🔭 **Creator of [Ruxen](https://github.com/ruxen-lang/ruxen)** — a compiled, statically-typed programming language that fuses Ruby's syntax with Rust's ownership model (no GC, native binaries).

I work mostly in **Ruby on Rails** and **TypeScript**, and I'm just as comfortable dropping into systems work (Rust, compilers) and AI/LLM tooling. I like building things that are hard to get right — language type-checkers, concurrency-safe systems, and tools other developers actually use.

## 🚀 Featured work

### [Ruxen](https://github.com/ruxen-lang/ruxen) · a programming language, built from scratch
A compiled, statically-typed language (Ruby-style syntax, Rust-style ownership, no garbage collector). A **~145K-line Rust compiler** with a full pipeline — lexer → bidirectional type inference → **ownership/borrow checker** → SSA-style MIR → **dual Cranelift + LLVM-18 backends** — plus an LSP, a JIT REPL, and a 31-module standard library written in the language itself. Dogfooded by three frameworks: a GUI engine ([canvas](https://github.com/ruxen-lang/canvas)), a reactive UI layer ([quiver](https://github.com/ruxen-lang/quiver)), and an async web server ([rondo](https://github.com/ruxen-lang/rondo)).
<br>`Rust` · `LLVM` · `Cranelift` · `compilers` · `~2,000 tests`

### braceful · a shipped, offline JSON dev tool — [live demo →](https://braceful.vercel.app)
A privacy-first browser extension that **repairs broken/truncated JSON** and renders **~100 MB files** in a virtualized tree via a **streaming tokenizer that runs entirely in a Web Worker** — so the tab never freezes and your data never leaves your machine. ~45K LOC TypeScript across the extension, a Cloudflare Workers billing backend, and a marketing site, backed by **1,400+ tests** and a perf-gated CI pipeline. *(Solo build; source private.)*
<br>`TypeScript` · `Web Workers` · `Cloudflare Workers` · `WXT` · `Playwright`

### Zoiro · a production-grade restaurant POS *(led; private — available on request)*
A **Rails 8 API + React/TypeScript** point-of-sale system I led (86% of commits). Recipe-based inventory that **can't oversell under concurrent orders** — proven by multi-threaded race tests using pessimistic DB locking — with a guarded order state machine and real-time multi-terminal sync over ActionCable. **1,150+ automated tests**, full CI/CD (Brakeman, RuboCop, bundler-audit).
<br>`Rails 8` · `React` · `TypeScript` · `ActionCable` · `MySQL`

### Open-source contributions *(merged, verifiable)*
**8 merged PRs** into public Ruby projects, including non-trivial refactors:
- [**foobara/foobara**](https://github.com/foobara/foobara/pulls?q=is%3Apr+author%3Asherazp995+is%3Amerged) — 5 PRs (e.g. *eliminate `.foobara_delegate` usages*, manifest API renames)
- [**foobara/rails-command-connector**](https://github.com/foobara/rails-command-connector/pull/2) — authored an auto-instantiating `RailsCommandConnector`
- [**leandrosardi/blackops**](https://github.com/leandrosardi/blackops/pulls?q=is%3Apr+author%3Asherazp995+is%3Amerged) — 2 PRs (file handling + single-binary packaging)

### Contributor @ [FlukeBase](https://flukebase.me) · AI-agent platform + SaaS cluster
I contribute features across a startup's Rails/Next.js product cluster — an agentic-development platform with a 600+ tool MCP server, plus shipped SaaS apps like [FounderSequence](https://foundersequence.com) and [FeelTrack](https://feeltrack.tech).

## 🛠️ Tech I reach for

| | |
|---|---|
| **Languages** | Ruby · TypeScript / JavaScript · Rust · Go · Python · Dart |
| **Backend** | Rails 8 · Node / Express · PostgreSQL · MySQL · ActionCable |
| **Frontend** | React · Vue · Next.js · Tailwind CSS |
| **Systems & tooling** | Compilers (LLVM / Cranelift) · MCP & LLM tooling · Docker · Kamal · Cloudflare Workers |

## 📊 GitHub

<p align="center">
  <img src="https://raw.githubusercontent.com/sherazp995/sherazp995/master/github-stats.svg" alt="Sheraz Aurang Zaib — GitHub stats" width="820">
</p>

---

<p align="center"><i>Open to remote full-stack / backend / developer-tooling roles. The fastest way to reach me is <a href="mailto:sherazp995@gmail.com">email</a> or <a href="https://www.linkedin.com/in/sherazp995">LinkedIn</a>.</i></p>
