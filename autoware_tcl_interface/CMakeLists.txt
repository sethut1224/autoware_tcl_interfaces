cmake_minimum_required(VERSION 3.14)
project(autoware_tcl_interface)

find_package(autoware_cmake REQUIRED)
autoware_package()

ament_auto_add_library(autoware_tcl_interface SHARED
  include/autoware_tcl_interface/autoware_tcl_interface.hpp
  src/autoware_tcl_interface.cpp
)


ament_auto_package()
