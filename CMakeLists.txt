cmake_minimum_required(VERSION 3.10)
project(Orderbook)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Include all source files
set(SOURCES
    main.cpp
    Orderbook.cpp
)

add_executable(Orderbook ${SOURCES})