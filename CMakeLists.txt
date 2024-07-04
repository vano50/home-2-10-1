cmake_minimum_required(VERSION 3.30)
project(my_first_cmake_project VERSION 0.1 LANGUAGES CXX)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ../build)
add_executable(my_first_cmake_program my_first_cmake_project.cpp)
