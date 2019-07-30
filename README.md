# 10,000 Cities with Latitude, Longitude, and Elevation

[![travis](https://img.shields.io/travis/tidwall/cities-rs.svg)](https://travis-ci.org/tidwall/cities-rs/)
[![version](https://img.shields.io/crates/v/cities.svg)](https://crates.io/crates/cities/)

<img src="http://i.imgur.com/i9hcVJ5.gif">

## Usage

The `all()` function returns a slice to the static cities array.

```rust
for city in cities::all(){
    println!("{:?}", city);
}
```


Looking for the [Go version](https://github.com/tidwall/cities)?

Animation created using [pinhole](https://github.com/tidwall/pinhole). 
