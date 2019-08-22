# CMake教程参考 https://www.hahack.com/codes/cmake/
#指定运行此配置文件所需的 CMake 的最低版本
cmake_minimum_required(VERSION 3.9)
# 该命令表示项目的名称
project(TestCC)

set(CMAKE_C_STANDARD 99)

# 将名为 Test.cpp 的源文件编译成一个名称为 TestCC 的可执行文件

add_executable(TestCC Test.cpp)