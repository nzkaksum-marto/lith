cmake_minimum_required(VERSION 3.20)

project(lithium VERSION 1.0 LANGUAGES CXX)

# Debug output
message(STATUS "Configuring project: ${PROJECT_NAME}")

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Define source files
set(SOURCES
    ${CMAKE_CURRENT_SOURCE_DIR}/src/main.cpp
)

# Debug output
message(STATUS "Source files: ${SOURCES}")

# Create executable target
add_executable(lith ${SOURCES})

# Debug output
message(STATUS "Created target: lith")