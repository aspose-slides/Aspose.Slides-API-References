---
title: GetFiles()
second_title: Aspose.Slides C++ API 参考
description: 返回一个数组，其中包含指向 FileInfo 对象的共享指针，这些对象表示当前对象所表示的目录中所有的子目录。
type: docs
weight: 157
url: /zh/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() 方法

返回一个数组，其中包含指向 [FileInfo](../../fileinfo/) 对象的共享指针，这些对象表示当前对象所表示的目录中所有的子目录。

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) 方法

在当前对象所表示的目录中搜索满足指定搜索条件的文件。

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的文件的名称模式 |

### 返回值

返回一个数组，其中包含指向 [FileInfo](../../fileinfo/) 对象的共享指针，这些对象表示名称匹配 **searchPattern** 的已找到文件。

## DirectoryInfo::GetFiles(const String\&, SearchOption) 方法

在当前对象所表示的目录或以该目录为根的整个目录树中搜索满足指定搜索条件的文件。

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的文件的名称模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜索是仅在当前对象所表示的目录中进行，还是在以该目录为根的整个目录树中进行 |

### 返回值

返回一个数组，其中包含指向 [FileInfo](../../fileinfo/) 对象的共享指针，这些对象表示名称匹配 **searchPattern** 的已找到文件。

## 另见

* 枚举 [SearchOption](../../searchoption/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [FileInfoPtr](../../../system/fileinfoptr/)
* 类 [DirectoryInfo](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)