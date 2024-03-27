<img src="/profile/orbitsystems.png" alt="Orbit Systems Logo" width="400"/>

# Orbit Systems

Orbit Systems is an organization centered around [**Aphelion**][Aphelion], a 64-bit [RISC][RISC]-like [*instruction set architecture*][ISA].

Aphelion aims to be a clean and featureful architecture without succumbing to paralyzing minimalism or unwieldy complexity, walking a line between [CISC][CISC] and [RISC][RISC] conventions. Aphelion is meant for high-performance, native 64-bit computing while staying easy to implement.

[Join our Discord here!](https://discord.gg/PzShtqpMKA)

## Projects

- [Comet][Comet] is the main Aphelion ISA reference emulator, written in C. It serves as the implementation reference for Aphelion.
- [Luna][Luna] is the main Aphelion assembler, written in C.
- [Mars][Mars] is statically-typed, procedural language for kernel and embedded programming. Mars focuses on low-level control, with emphasis on code configuration.

### Side projects

- [Nova][Nova] (also known as <https://nova.ferret.cafe>) is the Aphelion ISA online playground, written in Rust using WebAssembly. It includes an embedded assembler and emulator.
- [Meteor][Meteor] is an Aphelion ISA emulator, written in Rust. Meteor functions as a library with an example CLI for executing Aphelion code. Used in [Nova][Nova].
- [Terra][Terra] is an Aphelion assembler, written in Rust. Terra also functions as a library. Used in [Nova][Nova].
- [aphelion-util][util] ([lib.rs](https://lib.rs/crates/aphelion-util)) is a Rust library of types and traits useful for Aphelion programming.


[Aphelion]: https://github.com/orbit-systems/aphelion
[Comet]: https://github.com/orbit-systems/comet
[Luna]: https://github.com/orbit-systems/luna
[Mars]: https://github.com/orbit-systems/mars
[Nova]: https://github.com/orbit-systems/nova
[Meteor]: https://github.com/orbit-systems/meteor
[Terra]: https://github.com/orbit-systems/terra
[util]: https://github.com/orbit-systems/aphelion-util
[RISC]: https://en.wikipedia.org/wiki/Reduced_instruction_set_computer
[CISC]: https://en.wikipedia.org/wiki/Complex_instruction_set_computer
[ISA]: https://en.wikipedia.org/wiki/Instruction_set_architecture
