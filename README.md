# rust-book-exercises
rust-book-exercises


# Cargo

# open doc for crates 
cargo doc --open

# References
`&` is a reference indicator. Multiple Parts of code access the same piece of data.
References are immutable by default, `&mut` makes them mutable.

Example:

```rust
fn main() {
    // mutable reference
    let mut guess = String::new();
    std::io::stdin().read_line(&mut guess);
    
    // println! macro variables
    let x = 5;
    let y = 10;
    println!("x = {x} and y + 2 = {}", y + 2);
    
    // range expression from 1 (inclusive) to 100 (inclusive)
    let range = 1..=100; 

}
```