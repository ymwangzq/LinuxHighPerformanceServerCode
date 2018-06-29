cmake_minimum_required(VERSION 3.10)
project(5)

set(CMAKE_CXX_STANDARD 11)

add_executable(5
        5-10set_send_buffer.cpp
        5-11set_recv_buffer.cpp
        5-12access_daytime.cpp
        5-1byteorder.cpp
        5-3testlisten.cpp
        5-5testaccept.cpp
        5-6oobsend.cpp
        5-7oobrecv.cpp
        5-9reuse_address.cpp)
