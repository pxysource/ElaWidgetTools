# Qt Creator 15.0.0

1. 打开工程，打开顶层目录`CMakeLists.txt`。

2. 添加`Develop`配置。

   即：`Projects` -> `Run` -> `Deployment` -> `Add Deploy Step`，选择`CMake Install`。

3. `Build`（编译库）。

4. `Deploy`（安装库）。

5. 修改工程配置，设置`BUILD_ELAWIDGETTOOLS_EXAMPLE`为`ON`。

   即：`Projects` -> `CMake` -> `Current Configuration`，设置设置`BUILD_ELAWIDGETTOOLS_EXAMPLE`为`ON`。

6. `Build`（编译库和例子，由于库源代码没有更新，这一步只是编译例子）。