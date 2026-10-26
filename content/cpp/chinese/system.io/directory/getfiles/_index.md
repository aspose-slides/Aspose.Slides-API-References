---
title: GetFiles()
second_title: Aspose.Slides 的 C++ API 参考
description: 搜索满足指定搜索条件的文件，可在指定目录中或在以该目录为根的整个目录树中进行搜索。
type: docs
weight: 79
url: /zh/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) 方法

搜索满足指定搜索条件的文件，可在指定目录中或在以该目录为根的整个目录树中进行搜索。

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要搜索的目录的完整路径或相对路径 |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的文件的名称模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定是仅在指定目录中执行搜索，还是在以指定目录为根的整个目录树中执行搜索 |

### 返回值

一个包含所有文件完整路径的数组，这些文件的名称匹配 **searchPattern**

## 另请参见

* 枚举 [SearchOption](../../searchoption/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [String](../../../system/string/)
* 类 [Directory](../)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)