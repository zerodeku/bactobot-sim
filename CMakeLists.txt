cmake_minimum_required(VERSION 3.3)
project(bactobot_sim)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

message("${CMAKE_CXX_FLAGS}")

add_subdirectory(tests)

message("${PROJECT_BINARY_DIR}")