#
#HelloCmake
#Learn Cmake
#
#Created by Nguyen Quang Vuong on 16/05/2020
#Copyrighted © 2020 Nguyen Quang Vuong. All rights reserved

#Dieu kien ve version toi thieu doc duoc file CMakelist.txt
#
cmake_minimum_required(VERSION 2.8.12)
#
#Ten project la ten file chay
#
project (HelloCmake)

#
# Dinh nghia moi lien quan giua file chay va file nguon
#
add_executable(HelloCmake HelloCmake.cpp)