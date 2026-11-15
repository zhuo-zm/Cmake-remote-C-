# hello-cmake

这是一个使用 C++ 和 CMake 编写的简单示例项目。运行程序后，会在终端输出 `Hello, CMake!`。

## 项目结构

```text
hello-cmake/
├── CMakeLists.txt
├── include/
│   └── greeting.h
└── src/
    ├── greeting.cpp
    └── main.cpp
```

## 环境要求

- C++ 编译器
- CMake

## Debug 版本：构建和运行

在项目根目录打开终端，执行：

```bash
cmake -S . -B build-debug -DCMAKE_BUILD_TYPE=Debug
cmake --build build-debug
./build-debug/hello_cmake
```

运行结果应为：

```text
Hello, CMake!
```

## Release 版本：构建和运行

```bash
cmake -S . -B build-release -DCMAKE_BUILD_TYPE=Release
cmake --build build-release
./build-release/hello_cmake
```
