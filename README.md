### XXX

Simply use `setup.sh` to replace instances of `xxx` and `XXX` with your
project specific names and/or prefixes. This script also renames the files.

```sh
./setup.sh mylib
```

Then `mylib.sh` (Originally, `xxx.sh` before calling setup), can be used to
build and install the library `mylib.so` and the executable `mylib_driver`.
`setup.sh` self-deletes itself and deletes git history and this `README.md`
as well.
