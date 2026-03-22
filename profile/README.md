# StateForward

State machines as the universal runtime primitive. I build deterministic, event-driven frameworks where all application logic — branching, concurrency, time, and communication — is expressed through explicit hierarchical state machines.

No `if/else`. No implicit state. No side effects in transitions. Just machines, events, and run-to-completion semantics.

---

## Projects

### HSM — Hierarchical State Machine

A UML-compliant hierarchical state machine framework with a unified DSL across languages. Features include compound/orthogonal states, guards, effects, entry/exit actions, deferred events, submachines, timed events, and dependency injection.

| Language | Repo | Status |
| :--- | :--- | :--- |
| C++ | [`hsm.cpp`](https://github.com/stateforward/hsm.cpp) | Active — pure compile-time C++20 implementation |
| Go | [`hsm.go`](https://github.com/stateforward/hsm.go) | Active |
| Python | [`hsm.py`](https://github.com/stateforward/hsm.py) | Active |
| Rust | [`hsm.rs`](https://github.com/stateforward/hsm.rs) | Active |
| JavaScript | [`hsm.js`](https://github.com/stateforward/hsm.js) | Active |
| Zig | [`hsm.zig`](https://github.com/stateforward/hsm.zig) | Active |
| Dart | [`hsm.dart`](https://github.com/stateforward/hsm.dart) | Active |

### Proxyables — Transparent Remote Object Proxying

A peer-to-peer RPC library that makes remote objects feel local. Built on Yamux multiplexing, it provides bi-directional method invocation, distributed garbage collection, stream pooling, and automatic callback hydration — all over a single connection.

| Language | Repo | Status |
| :--- | :--- | :--- |
| Go | [`proxyables.go`](https://github.com/stateforward/proxyables.go) | Active |
| Python | [`proxyables.py`](https://github.com/stateforward/proxyables.py) | Active |
| Rust | [`proxyables.rs`](https://github.com/stateforward/proxyables.rs) | Active |
| TypeScript | [`proxyables.ts`](https://github.com/stateforward/proxyables.ts) | Active |
| Zig | [`proxyables.zig`](https://github.com/stateforward/proxyables.zig) | Active |

### Emel — Deterministic ML Inference

A deterministic, event-driven machine learning inference engine built on explicit state machines for predictable, high-performance execution.

| Language | Repo | Status |
| :--- | :--- | :--- |
| C++ | [`emel.cpp`](https://github.com/stateforward/emel.cpp) | Active — core engine |
| Go | [`emel.go`](https://github.com/stateforward/emel.go) | Active — Go FFI bindings via [purego](https://github.com/ebitengine/purego) |
| Python | [`emel.py`](https://github.com/stateforward/emel.py) | Active — Python FFI bindings |

---

## License

All public repositories are MIT licensed.
