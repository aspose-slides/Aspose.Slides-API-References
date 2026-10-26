---
title: EnumerateFiles()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个可枚举集合，包含当前对象所表示的目录中的所有文件。
type: docs
weight: 118
url: /zh/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() 方法

返回一个可枚举集合，包含当前对象所表示目录中的所有文件。

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) 方法

在当前对象所表示的目录中搜索满足指定搜索条件的文件。

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的文件的名称模式 |

### 返回值

可枚举的集合，包含指向 [FileInfo](../../fileinfo/) 对象的共享指针，这些对象表示名称匹配 **searchPattern** 的找到的文件。

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) 方法

在当前对象所表示的目录或以该目录为根的整个目录树中搜索满足指定搜索条件的文件。

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的文件的名称模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜索是仅在当前对象所表示的目录中进行，还是在以该目录为根的整个目录树中进行 |

### 返回值

可枚举的集合，包含指向 [FileInfo](../../fileinfo/) 对象的共享指针，这些对象表示名称匹配 **searchPattern** 的找到的文件。

## 另见

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)