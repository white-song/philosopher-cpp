cmake_minimum_required(VERSION 3.21)
project(philosopher_cpp)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(philosopher_cpp
        main.cpp)
