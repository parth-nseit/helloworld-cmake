cmake_minimum_required(VERSION 2.8.12)
project(Hello)

ADD_LIBRARY(hello hello.h hello.cpp)
ADD_EXECUTABLE(greeting main.cpp)
TARGET_LINK_LIBRARIES(greeting hello)
