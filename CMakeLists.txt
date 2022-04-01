cmake_minimum_required(VERSION 3.14...3.22) 
project(log VERSION 1.0 LANGUAGES C)

add_library(log STATIC src/log.c src/log.h)
