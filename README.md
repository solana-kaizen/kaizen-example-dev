# workflow-allocator-example-dev

Build package for the [workflow-allocator-example](https://github.com/workflow-rs/workflow-allocator-example) repository.

### Prerequisites

Command line `git`

To build:

```
cargo install cargo-emanate
git clone https://github.com/workflow-rs/workflow-allocator-example-dev
cd workflow-allocator-example-dev
cargo emanate sync
```

Following this, you can go to `workflow-allocator-example-dev/workflow-allocator-example` and build internal crates.
