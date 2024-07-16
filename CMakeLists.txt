cmake_minimum_required(VERSION 3.24)
project(SoftwareEngineering)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(SoftwareEngineering
        luhn.cpp
        luhn.h
        main.cpp)
