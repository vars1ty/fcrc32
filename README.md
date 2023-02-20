# FCRC32
Force the CRC32 of any file to your own value.
## Credit
> **Note** This was developed by Nayuki and released for free under the GPL license [here](https://www.nayuki.io/page/forcing-a-files-crc-to-any-value), I just turned it into a library rather than an executable.
# Usage Example
```rust
process("/home/user/doc.txt", "11111111", 0, false).unwrap()
