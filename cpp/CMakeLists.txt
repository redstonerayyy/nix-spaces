cmake_minimum_required(VERSION 3.26)
project(cpp-nix VERSION 1.0 LANGUAGES CXX)

find_package(Boost REQUIRED)

add_executable(main main.cpp)

target_link_libraries(main PRIVATE Boost::boost)
