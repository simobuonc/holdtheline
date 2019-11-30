cmake_minimum_required(VERSION 2.6)
project(holdtheline)

add_executable(holdtheline main.cpp)

install(TARGETS holdtheline RUNTIME DESTINATION bin)
