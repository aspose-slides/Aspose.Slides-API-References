---
title: GetDirectories()
second_title: Aspose.Slides for C++ API 参考
description: 在指定目录中或在以指定目录为根的整个目录树中搜索满足指定搜索条件的目录。
type: docs
weight: 66
url: /zh/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) method

搜索满足指定搜索条件的目录，可在指定目录中或在以指定目录为根的整个目录树中进行搜索。

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要搜索的目录的完整或相对路径 |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的目录的名称模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定是仅在指定目录中搜索，还是在以指定目录为根的整个目录树中搜索 |

### 返回值

一个包含找到的目录完整路径的数组，这些目录的名称与 **searchPattern** 匹配

## 另请参见

* 枚举 [SearchOption](../../searchoption/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [Directory](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)