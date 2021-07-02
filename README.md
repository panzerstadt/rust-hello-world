# to run

## mac:

- double click on app in executable/hello_world

## windows:

- double click on app in executable/hello_world.exe (it would run and exit)
- OR open powershell, navigate to the exe file, then type `./hello_world.exe`. you should see the command line program run, print your program output, and exit.

# to compile (mac)

1. have rustup installed (type `rustup --version` in your terminal to check for existence)
2. now you should have cargo (it's rust's npm)
3. run `cargo build`
4. run `cargo run`
5. hit f5 to debug, with breakpoints and everything

# to compile (windows)

1. must be able to compile mac (see above)
2. compile with cross (https://github.com/rust-embedded/cross) - must have docker on your system already
3. `cross build --target x86_64-pc-windows-gnu`
4. you should now have your exe file in target/x86_64-pc-windows-gnu
