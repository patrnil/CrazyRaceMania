cmake_minimum_required(VERSION 3.15)
project(CrazyRaceMania)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra -Wconversion")

include_directories(include)
add_executable(CrazyRaceMania
        src/main.cpp
        )
