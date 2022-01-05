cmake_minimum_required(VERSION 3.21)
project(games101)

set(CMAKE_CXX_STANDARD 14)

add_subdirectory(eigen3)
add_subdirectory(pa0)

add_executable(games101 main.cpp)
