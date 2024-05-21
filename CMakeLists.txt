set( CMAKE_CXX_COMPILER "C:/MinGW/bin/g++" )
set( CMAKE_C_COMPILER "C:/MinGW/bin/gcc" )

cmake_minimum_required(VERSION 3.5)
project(example)
add_executable(${PROJECT_NAME} main.cpp)