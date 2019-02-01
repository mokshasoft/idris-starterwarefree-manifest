# idris-starterwarefree-manifest - Project to build bare-metal Idris applications on TI StarterWare
No code has been written yet. The below commands will not currently build any software.

## Get the Code!

Run the following commands to get the code:
```
mkdir idris-starterwarefree-manifest
cd idris-starterwarefree-manifest
repo init -u https://github.com/mokshasoft/idris-starterwarefree-manifest.git
repo sync
```

## Build it

Run the following commands to build and run it:

```
mkdir build
cd build
cmake -G Ninja -DCMAKE_TOOLCHAIN_FILE=../starterwarefree/build/CMake/gcc.cmake ..
ninja led-blink
```
