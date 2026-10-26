---
title: EnumerateFiles()
second_title: Aspose.Slides for C++ API 参考
description: 在指定目录或以该目录为根的整个目录树中搜索满足指定搜索条件的文件。
type: docs
weight: 40
url: /zh/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String\&, const String\&, SearchOption) 方法

搜索满足指定搜索条件的文件，可在指定目录中或在以该目录为根的整个目录树中进行搜索。

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要搜索的目录的完整路径或相对路径 |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的文件的名称模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定是仅在指定目录中执行搜索，还是在以指定目录为根的整个目录树中执行搜索 |

### 返回值

可枚举的集合，包含所有名称匹配 **searchPattern** 的已找到文件的完整路径

## 另请参见

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)