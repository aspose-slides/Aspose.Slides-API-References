---
title: GetFileSystemEntries()
second_title: Aspose.Slides for C++ API 参考
description: 搜索满足指定搜索条件的文件和目录，可在指定目录中或在以指定目录为根的整个目录树中进行搜索。
type: docs
weight: 92
url: /zh/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) 方法

搜索满足指定搜索条件的文件和目录，可以在指定目录中或在以指定目录为根的整个目录树中进行搜索。

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要搜索的目录的完整或相对路径 |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的文件和目录的名称模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定是仅在指定目录中执行搜索还是在以指定目录为根的整个目录树中执行搜索 |

### 返回值

一个数组，包含匹配**searchPattern**的已找到文件和目录的完整路径

## 另见

* 枚举 [SearchOption](../../searchoption/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [Directory](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)