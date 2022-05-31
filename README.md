## 简单c++库的标准
* 不依赖额外的c/c++代码, 并且满足以下任意条件
  * 只包含1个头文件: xxx.h或者xxx.hpp (header only)
  * 只包含2个文件: xxx.h、xxx.cpp
### 考虑的问题
* header only 模式编译速度慢
* 在开发期间可以将代码分割到不同文件，发布时候需要满足**简单c++库的标准**，可以使用工具合并相关代码
### 目前已知符合“简单c++库标准”的库列表
* [tinyxml2](https://github.com/leethomason/tinyxml2)
* [sqlite3](https://www.sqlite.org/index.html)
