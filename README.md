```
$ cargo tree
bookish-octo-chainsaw v0.1.0 (/home/seth/Code/src/github.com/sethp/bookish-octo-chainsaw)
├── esp-alloc v0.1.0
│   ├── bare-metal v1.0.0
│   ├── linked_list_allocator v0.10.5
│   └── riscv v0.8.0
│       ├── bare-metal v1.0.0
│       ├── bit_field v0.10.2
│       └── embedded-hal v0.2.7
│           ├── nb v0.1.3
│           │   └── nb v1.1.0
│           └── void v1.0.2
└── riscv-rt v0.11.0
    ├── r0 v1.0.0
    ├── riscv v0.10.1 (registry `https://github.com/rust-lang//crates.io-index`)
    │   ├── bit_field v0.10.2 (registry `https://github.com/rust-lang//crates.io-index`)
    │   ├── critical-section v1.1.1 (registry `https://github.com/rust-lang//crates.io-index`)
    │   └── embedded-hal v0.2.7 (registry `https://github.com/rust-lang//crates.io-index`)
    │       ├── nb v0.1.3 (registry `https://github.com/rust-lang//crates.io-index`)
    │       │   └── nb v1.1.0 (registry `https://github.com/rust-lang//crates.io-index`)
    │       └── void v1.0.2 (registry `https://github.com/rust-lang//crates.io-index`)
    └── riscv-rt-macros v0.2.0 (proc-macro)
        ├── proc-macro2 v1.0.52
        │   └── unicode-ident v1.0.8
        ├── quote v1.0.26
        │   └── proc-macro2 v1.0.52 (*)
        └── syn v1.0.109
            ├── proc-macro2 v1.0.52 (*)
            ├── quote v1.0.26 (*)
            └── unicode-ident v1.0.8
    [build-dependencies]
    └── riscv-target v0.1.2
        ├── lazy_static v1.4.0
        └── regex v1.7.1
            ├── aho-corasick v0.7.20
            │   └── memchr v2.5.0
            ├── memchr v2.5.0
            └── regex-syntax v0.6.28
[dev-dependencies]
└── riscv v0.7.0
    ├── bare-metal v1.0.0
    └── bit_field v0.10.2
    [build-dependencies]
    └── riscv-target v0.1.2 (*)
```
