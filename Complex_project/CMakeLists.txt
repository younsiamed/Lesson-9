cmake_minimum_required(VERSION 3.22.2)
project(Complex_project)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)
add_executable(Complex_project 
               src/main.cpp 
               src/Source\ Files/Triangle.cpp
               src/Source\ Files/RightTriangle.cpp
               src/Source\ Files/IsoscelesTriangle.cpp
               src/Source\ Files/EquilateralTriangle.cpp
               src/Source\ Files/Quadrilateral.cpp
               src/Source\ Files/Rectangle.cpp
               src/Source\ Files/Square.cpp
               src/Source\ Files/Parallelogram.cpp
               src/Source\ Files/Rhombus.cpp
               src/Source\ Files/Figure.cpp)
target_include_directories(Complex_project PRIVATE src/Header\ Files)