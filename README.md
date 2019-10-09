# mem_proc
How to cross compile for embeded linux?
add the following in CMakeLists.txt:
SET(CMAKE_SYSTEM_NAME Linux)
SET(CMAKE_C_COMPILER "arm-linux-gnueabihf-gcc")
