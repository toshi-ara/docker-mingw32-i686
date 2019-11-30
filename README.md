# toshiara/mingw32-i686

Minimalist GNU C/C++ for Windows.

- base docker image file is debian:10-slim
- add i686-mingw32-i686-gcc/g++/gfortran


## Build

```bash
$ https://github.com/toshi-ara/docker-mingw32-i686.git
$ cd docker-mingw32-i686
$ sudo ./build.sh
```

## Usage

```bash
$ docker run --rm -it -v ${PWD}:/workdir toshiara/mingw32-i686 i686-w64-mingw32-gcc --version --version
```

## License

MIT (c) ARA Toshiaki

