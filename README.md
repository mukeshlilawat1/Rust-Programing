<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=DEA584&height=200&section=header&text=Rust%20Programming&fontSize=40&fontColor=1a1a1a&animation=fadeIn&desc=Systems%20Programming%2C%20Safely%20and%20Fast&descAlignY=65&descSize=18&fontColor=ffffff" />

**A structured learning repository for mastering Rust — from core syntax to ownership, concurrency, and real-world systems programming.**

<img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/Cargo-DEA584?style=for-the-badge&logo=rust&logoColor=black" />
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />

<br/>

**[Getting Started](#-getting-started)** • **[Structure](#️-repository-structure)** • **[Learning Path](#-learning-path)** • **[Topics](#-topics-covered)** • **[Contributing](#-contributing)**

</div>

---

## 📖 About

Rust is a systems programming language focused on **speed, memory safety, and fearless concurrency** — all without a garbage collector. This repository is my personal journey learning Rust: notes, exercises, and small projects as I build fluency in the language and its ecosystem.

## 🗂️ Repository Structure

```
rust-learning/
├── introduction/            # Setup, syntax basics, cargo essentials
├── ownership-borrowing/     # Ownership, borrowing, lifetimes
├── data-structures/         # Vectors, HashMaps, Structs, Enums
├── error-handling/          # Result, Option, panic!, custom errors
├── traits-generics/         # Traits, generics, trait objects
├── concurrency/             # Threads, channels, Arc, Mutex
├── async-rust/              # async/await, tokio basics
├── projects/                # Small end-to-end Rust projects
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- [Rust toolchain](https://www.rust-lang.org/tools/install) (via `rustup`)
- A code editor (VS Code + `rust-analyzer` recommended)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/mukeshlilawat1/rust-learning.git
cd rust-learning

# 2. Verify Rust & Cargo are installed
rustc --version
cargo --version

# 3. Run any project with Cargo
cd projects/<project-name>
cargo run

# 4. Run tests
cargo test
```

## 📖 Learning Path

<table>
<tr>
<td valign="top" width="33%">

**🔰 Beginner**
1. Install Rust via `rustup`
2. Learn variables, types, functions
3. Understand `cargo` basics
4. Practice control flow & pattern matching

</td>
<td valign="top" width="33%">

**🎓 Intermediate**
1. Master ownership, borrowing & lifetimes
2. Work with structs, enums & traits
3. Handle errors with `Result` / `Option`
4. Explore collections (`Vec`, `HashMap`)

</td>
<td valign="top" width="33%">

**🚀 Advanced**
1. Generics & trait objects
2. Concurrency (threads, `Arc`, `Mutex`)
3. Async Rust with `tokio`
4. Build & publish real crates

</td>
</tr>
</table>

## 🧠 Topics Covered

| Category | Status |
|---|:---:|
| Variables, Types & Functions | ✅ |
| Ownership, Borrowing & Lifetimes | 🔄 |
| Structs, Enums & Pattern Matching | 🔄 |
| Error Handling (`Result`, `Option`) | ⏳ |
| Traits & Generics | ⏳ |
| Collections & Iterators | ⏳ |
| Concurrency & Multithreading | ⏳ |
| Async Rust (`tokio`) | ⏳ |
| Testing & Cargo Ecosystem | ⏳ |

> ✅ Done &nbsp;&nbsp; 🔄 In Progress &nbsp;&nbsp; ⏳ Upcoming

## 🎨 Projects

| Project | Description |
|---|---|
| 🧮 **CLI Calculator** | A command-line calculator using enums & pattern matching |
| 📋 **Todo App** | File-backed todo manager using structs & error handling |
| 🌐 **Mini HTTP Server** | A basic multithreaded TCP/HTTP server |
| 🔗 **Concurrent Word Counter** | Multithreaded file processing with channels |
| ⚡ **Async Web Scraper** | Concurrent scraping using `tokio` and `reqwest` |

*More projects coming soon!*

## 🛠️ Tools & Ecosystem

<div align="center">

<img src="https://img.shields.io/badge/rustup-DEA584?style=flat-square&logo=rust&logoColor=black" />
<img src="https://img.shields.io/badge/Clippy-000000?style=flat-square&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/tokio-000000?style=flat-square" />
<img src="https://img.shields.io/badge/serde-000000?style=flat-square" />
<img src="https://img.shields.io/badge/rust--analyzer-DEA584?style=flat-square&logo=rust&logoColor=black" />

</div>

- **Toolchain**: `rustup`, `cargo`, `rustc`
- **Linting/Formatting**: `clippy`, `rustfmt`
- **Async runtime**: `tokio`
- **Serialization**: `serde`, `serde_json`
- **Editor support**: `rust-analyzer`

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📚 Resources

<table>
<tr>
<td valign="top" width="33%">

**📕 Books**
- *The Rust Programming Language* (official book)
- *Programming Rust* — O'Reilly
- *Rust for Rustaceans* — Jon Gjengset

</td>
<td valign="top" width="33%">

**🎓 Courses & Practice**
- [Rustlings](https://github.com/rust-lang/rustlings)
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
- Exercism Rust Track

</td>
<td valign="top" width="33%">

**🔗 References**
- [docs.rs](https://docs.rs)
- [crates.io](https://crates.io)
- The Rust Standard Library docs

</td>
</tr>
</table>

## 📬 Contact

**Mukesh Lilawat**
GitHub: [@mukeshlilawat1](https://github.com/mukeshlilawat1)

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**⭐ Star this repository if you find it helpful!**

<img src="https://capsule-render.vercel.app/api?type=waving&color=DEA584&height=100&section=footer" />

</div>
