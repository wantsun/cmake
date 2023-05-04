cmake_minimum_required(VERSION 3.25 FATAL_ERROR)

project(cmake LANGUAGES C CXX)

list(APPEND CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}/cmake")
include(Buildinfo)

add_subdirectory(src)
add_subdirectory(external)
add_subdirectory(docs)
add_subdirectory(test)
