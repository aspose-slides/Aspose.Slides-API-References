---
title: EnumerateFileSystemEntries()
second_title: Aspose.Slides C++ API 参考
description: 搜索满足指定搜索条件的文件和目录，可以在指定目录中或在以该目录为根的整个目录树中进行搜索。
type: docs
weight: 53
url: /zh/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String&, const String&, SearchOption) 方法

搜索满足指定搜索条件的文件和目录，可以在指定目录中或在以该目录为根的整个目录树中进行搜索。

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要搜索的目录的完整或相对路径 |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的文件和目录的名称模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜索是仅在指定目录中进行，还是在以该目录为根的整个目录树中进行 |

### 返回值

返回一个可枚举的集合，包含所有名称匹配 **searchPattern** 的已找到文件和目录的完整路径

## 另请参阅

* 枚举 [SearchOption](../../searchoption/)
* 类型定义 [StringEnumerablePtr](../stringenumerableptr/)
* 类 [String](../../../system/string/)
* 类 [Directory](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)