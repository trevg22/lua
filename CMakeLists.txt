cmake_minimum_required(VERSION 3.14)
project(lua LANGUAGES C)

add_library(lua STATIC)
add_subdirectory(src)
target_include_directories(lua INTERFACE src)
