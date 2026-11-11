# RIGCOM — Sovereign Ecosystem in C

**A complete system built from scratch, with zero external dependencies in the core. Organized into 14 independent products.**

RIGCOM is Richard Felipe Urbina's flagship ecosystem: his own platform, network, compiler, browser and search engine, and local AI — everything finished, verified and organized so each product can be shown, sold or commissioned separately.

## The 14 products

1. **Platform and Core** — own libc (riglibc), direct syscalls for ARM64, x86_64, Android and Linux; a "noext" core with zero external dependencies
2. **Security, Identity and Codes** — own QR generator and SovereignCode, a proprietary code in a Fibonacci spiral with Reed-Solomon correction, plus identity, vault and cryptography
3. **Data** — data, configuration and cache for the ecosystem
4. **Network and Protocols** — own DNS and DNS over HTTPS, HTTP, QUIC, TLS, SOCKS5, SSH, MQTT and a TUN engine
5. **Communication and Email** — P2P messaging with its own relay, MTProto, own SMTP email and a bridge to Telegram
6. **Sovereign Compiler** — front ends for C, C++, Go, Java, Kotlin, Lua, Python, Swift, TypeScript and Zig, plus RigScript, my own language in 13 variants; outputs to ARM64 and WebAssembly
7. **Build and Self-Building** — HGEN header generator, self-building, hot reload and cross-compilation to ARM64
8. **Browser and Search** — HTML parser, CSS engine, DOM, a JavaScript engine with a virtual machine, a crawler and a search engine with its own index
9. **Graphics, UI, RigArt and Avatar** — generative 3D face and avatar engine with ARKit and VRM export, ray tracing and the Catedral interface (HOME + 14 apps)
10. **Android and APK** — the RIGFORGE core: build, sign and inspect APKs, a binder driver, zero JNI and ADB
11. **Developer Tools** — an LSP language server, a DAP debugger via ptrace, a PTY terminal and a "doctor" diagnostic tool
12. **RIGADIEL — Local AI** — on-device training and inference, tokenizer, reasoning, graph, sessions and voice
13. **Shell and Operating System** — a shell with 91 semantic commands (adb, apk, build, lsp, doctor, bridge...)
14. **Validation and Integration** — integrity verification of the whole ecosystem and its test suite

## Verified figures

- 596 source files, verified one by one with SHA-256 (596 of 596 intact)
- About 333,000 lines of code, all in C · about 20 MB · 12,524 prototypes
- 15 of 15 tests passed · 0 external dependencies in the core

## Presentation repository

This is a presentation repository for the RIGCOM ecosystem. The full source is Richard's own asset, available by commission — not uploaded in bulk here. Featured product: RIGFORGE V40, the on-device APK forge.

## Links

- Portfolio (English): https://rigdevia.github.io/en/
- Portfolio (Spanish): https://rigdevia.github.io/
- Author: Richard Felipe Urbina — [@rigdevIA](https://github.com/rigdevIA) — Zapopan, Jalisco, Mexico (remote)
- Contact: rigaful2@gmail.com
- Languages: Spanish (native) · English (basic)
