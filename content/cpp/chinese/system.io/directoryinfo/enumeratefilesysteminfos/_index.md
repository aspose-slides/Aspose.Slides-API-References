---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides C++ API 参考
description: 返回一个可枚举的集合，包含当前对象所表示的目录中所有的文件和目录。
type: docs
weight: 131
url: /zh/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() 方法

返回一个可枚举的集合，包含当前对象所表示的目录中所有的文件和目录。

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) 方法

在当前对象所表示的目录中搜索满足指定搜索条件的文件和目录。

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 用于搜索的文件和目录的名称模式 |

### 返回值

返回一个可枚举的集合，包含指向 [FileSystemInfo](../../filesysteminfo/) 对象的共享指针，这些对象表示名称与 **searchPattern** 匹配的已找到的文件和目录。

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) 方法

在当前对象所表示的目录或以该目录为根的整个目录树中搜索满足指定搜索条件的文件和目录。

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 用于搜索的文件和目录的名称模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜索是仅在当前对象所表示的目录中进行，还是在以该目录为根的整个目录树中进行 |

### 返回值

返回一个可枚举的集合，包含指向 [FileSystemInfo](../../filesysteminfo/) 对象的共享指针，这些对象表示名称与 **searchPattern** 匹配的已找到的文件和目录。

## 另请参阅

* 枚举 [SearchOption](../../searchoption/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类型别名 [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 类 [DirectoryInfo](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::IO](../../)
* 库 [Aspose.Slides](../../../)