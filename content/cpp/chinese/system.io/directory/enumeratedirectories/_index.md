---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API 参考
description: 搜索满足指定搜索条件的目录，可在指定目录中或在以该目录为根的整个目录树中进行搜索。
type: docs
weight: 27
url: /zh/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) 方法

搜索满足指定搜索条件的目录，可在指定目录中或在以该目录为根的整个目录树中进行搜索。

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要搜索的目录的完整路径或相对路径 |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的目录的名称模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜索是仅在指定目录中进行，还是在以该目录为根的整个目录树中进行 |

### 返回值

可枚举的集合，包含所有名称符合 **searchPattern** 的找到的目录的完整路径

## 另请参见

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)