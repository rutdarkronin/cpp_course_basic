cmake_minimum_required(VERSION 3.5)

project(01.hello_world)

add_executable(hello_world 
    source/hello_world.cpp
    source/example.cpp
    source/example.h
    source/move_me_out.h
    source/move_me_out.cpp
)

set_target_properties(hello_world PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED ON
)