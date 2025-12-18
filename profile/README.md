# Render Protocol

**Render Protocol** is an open-source, **server-driven UI framework** for modern mobile platforms, starting with **SwiftUI** and **Flutter**, and expanding to **Jetpack Compose**.

The goal is to enable **dynamic, schema-driven UIs** powered by backend configuration and AI systems — without sacrificing native performance or platform idioms.

> 🚧 This project is in its **early foundation phase**.  
> Repositories are currently initialized as **blank packages** while architecture and core schemas are being finalized.

---

## 🎯 Vision

Build a **platform-agnostic UI rendering protocol** that allows:

- Rendering native UI from **JSON / schema definitions**
- Backend-controlled UI updates without app redeploys
- AI systems (LLMs) to generate **valid, renderable UI schemas**
- Strong separation of **design, logic, and presentation**
- First-class support for **mobile-only experiences**

Render Protocol is **not a web abstraction layer** — it embraces native frameworks and performance.

---

## 🧠 Core Principles

- **Server-Driven, Native-Rendered**
- **Schema First**
- **Mobile-Only Focus**
- **AI-Compatible UI Generation**
- **Open-Source & Self-Hostable**
- **Extensible & Incremental**

---

## 🗺️ Roadmap (High Level)

### Phase 1 – Foundations (Current)
- Define platform-generic UI schema
- Client-side renderers for SwiftUI & Flutter
- Networking, caching, and schema validation
- Authentication hooks

### Phase 2 – AI & Tooling
- LLM-friendly schema definitions
- UI generation during user interaction
- Schema introspection & validation tools
- Drag-and-drop UI builder (backend-driven)

### Phase 3 – Ecosystem
- Jetpack Compose parity
- Protobuf / binary schema support
- Performance instrumentation
- Advanced state & event handling

---

## 📦 Repositories

### 🧩 Client SDKs

#### **RenderProtocolSwift**
Native Swift package for **SwiftUI** rendering.

Planned features:
- Schema → SwiftUI renderer
- Native layout & styling mapping
- State & action handling
- Networking, cache & auth modules

Status: **Initialized (empty package)**

---

#### **fl_render_protocol**
Flutter implementation of Render Protocol.

Planned features:
- Schema → Flutter widget renderer
- Platform-agnostic UI definitions
- Shared schema compatibility with SwiftUI

Status: **Initialized (empty package)**

---

#### **render-protocol-compose**
Jetpack Compose (Kotlin) renderer.

Planned features:
- Schema → Compose UI mapping
- Android-first optimizations
- Parity with SwiftUI & Flutter APIs

Status: **Initialized (empty package)**

---

### 🖥️ Backend

#### **render_protocol_server**
Backend reference implementation.

Planned features:
- Schema storage & versioning
- Authentication & authorization
- UI delivery APIs
- Future UI builder & AI integration

Language/runtime is intentionally flexible to allow experimentation.

Status: **Initialized (empty package)**

---

## 🤖 AI-First Thinking

Render Protocol is designed so that:

- An LLM can **reason about supported UI components**
- Generated responses can return **UI instead of text**
- Client SDKs can safely render AI-generated layouts

This enables:
- Conversational UIs
- Adaptive screens
- Context-aware layouts

---

## 🌱 Project Status

- Early architecture & schema design phase
- APIs and folder structures are **not final**
- Expect breaking changes during v0.x
- Contributions & discussions welcome once foundations are set

---

## 🔗 Learn More

- GitHub Org: https://github.com/renderprotocol

---

## 📜 License

Licensing details will be finalized once core architecture stabilizes.
The intent is to keep Render Protocol **open, extensible, and community-friendly**.

---

**Render once. Control everywhere.**
