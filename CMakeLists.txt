cmake_minimum_required(VERSION 2.8.0)
add_executable(lisp main.c lisp.c parse.c print.c symbol.c primitive.c eval.c)

set(CMAKE_C_FLAGS "-Wall -std=c99")
