cmake_minimum_required(VERSION 3.7)
project(tests LANGUAGES C)

set(CMAKE_C_STANDARD 99)

add_executable(converter /src/Converter/Converter.c /src/Converter/myinterpritation.c /src/Converter/myinterpritation.h /src/Converter/qdbmp.c /src/Converter/qdbmp.h
add_executable(comparer /src/Converter/comparer.c 


