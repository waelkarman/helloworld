cmake_minimum_required(VERSION 3.15)

include(GNUInstallDirs)

project(helloworld)

add_executable(helloworld main.cpp)

install(TARGETS helloworld RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR})