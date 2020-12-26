cmake_minimum_required(VERSION 3.3)
project(embed)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.c socket_test.c server.c server.h client.c)
add_executable(embed ${SOURCE_FILES})