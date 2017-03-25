# lemon-parser-generator
Lemon parser generator (extracted from SQLite)
- `lemon.c` keeps Lemon implementation
- `lempar.c` is template file for code generation

You should distribute `lemon` executable and `lempar.c` template file together

## How to Build
With CMake and Visual Studio 2015:
```bash
cmake -DCMAKE_BUILD_TYPE=Release -G "Visual Studio 2015" .
# now open lemon.sln and build
```
With CMake on Linux:
```bash
cmake -DCMAKE_BUILD_TYPE=Release . && make -s
```
You can also build `lemon.c` manually.
