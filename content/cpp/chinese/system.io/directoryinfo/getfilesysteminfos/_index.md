---
title: GetFileSystemInfos()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个数组，包含指向 FileSystemInfo 对象的共享指针，这些对象表示当前对象所代表的目录中的所有文件和目录。
type: docs
weight: 170
url: /zh/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() 方法

返回一个数组，其中包含指向 [FileSystemInfo](../../filesysteminfo/) 对象的共享指针，这些对象表示当前对象所代表的目录中的所有文件和目录。

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) 方法

在当前对象所代表的目录中搜索满足指定搜索条件的文件和目录。

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的文件和目录的名称模式 |

### 返回值

一个数组，包含指向 [FileSystemInfo](../../filesysteminfo/) 对象的共享指针，这些对象表示名称匹配 **searchPattern** 的已找到文件和目录。

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) 方法

在当前对象所代表的目录或以当前对象所代表的目录为根的整个目录树中搜索满足指定搜索条件的文件和目录。

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的文件和目录的名称模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜索是仅在当前对象所代表的目录中进行，还是在以该目录为根的整个目录树中进行 |

### 返回值

一个数组，包含指向 [FileSystemInfo](../../filesysteminfo/) 对象的共享指针，这些对象表示名称匹配 **searchPattern** 的已找到文件和目录。

## 另见

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)