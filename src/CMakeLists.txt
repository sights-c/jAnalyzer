cmake_minimum_required(VERSION 2.6.0)
PROJECT(JANALYZER)

SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Woverloaded-virtual -Wshadow -Wextra")

# Use your own library
# add_library(${name} $(directory))

add_executable(jAnalyzer jAnalyzer.cpp)
	
INSTALL(TARGETS jAnalyzer DESTINATION bin)	


