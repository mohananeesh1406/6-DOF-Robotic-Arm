cmake_minimum_required(VERSION 3.8)
project(urdf_assembly)

find_package(ament_cmake REQUIRED)

install(DIRECTORY launch meshes urdf config
  DESTINATION share/${PROJECT_NAME})

ament_package()