# Greatest common divisor
Calculates the greates common divisor of the given numbers.

## Usage
```bash
cargo run 10 24 45 67 78

 Finished dev [unoptimized + debuginfo] target(s) in 0.00s
     Running `target/debug/gcd 10 24 45 67 78`
The greatest common divisor of [10, 24, 45, 67, 78] is 1
```

## Run tests
```bash
cargo test

   Compiling gcd v0.1.0 (/Users/tkircsi/personal/rust/programming-rust/gcd)
    Finished test [unoptimized + debuginfo] target(s) in 0.70s
     Running unittests src/main.rs (target/debug/deps/gcd-f841dcf116822c24)

running 2 tests
test test_gcd ... ok
test invalid_param - should panic ... ok

test result: ok. 2 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.00s
```
