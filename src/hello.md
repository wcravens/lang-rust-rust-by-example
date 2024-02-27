# Hello World

This is the source code of the traditional Hello World program.

```rust,editable
fn main() {
    println!("Hello World!");
}
```

`println!` is a [*macro*][macros] that prints text to the
console.

A binary can be generated using the Rust compiler: `rustc`.

```bash
$ rustc hello.rs
```

`rustc` will produce a `hello` binary that can be executed.

```bash
$ ./hello
Hello World!
```

### Activity

Click 'Run' above to see the expected output. Next, add a new
line with a second `println!` macro so that the output shows:

```text
Hello World!
I'm a Rustacean!
```

[macros]: macros.md
