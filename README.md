# Not Maintained
## Will be removed later

From now on, use the following in your `Move.toml`:
```
[dependencies.MoveStdlib]
git = "https://github.com/move-language/move.git"
rev = "b53bb030b556a4e6ac2728d50ec7baaddf0b9a56"
subdir = "language/move-stdlib"
addr_subst = { "std" = "0x1" }
```

(The build system can nowadays pick
the correct version by commit hash and path.)
