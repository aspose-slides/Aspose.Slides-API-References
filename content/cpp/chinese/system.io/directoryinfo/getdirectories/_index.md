---
title: GetDirectories()
second_title: Aspose.Slides C++ API 参考
description: 返回一个数组，其中包含指向 DirectoryInfo 对象的共享指针，这些对象表示当前对象所代表的目录中所有的子目录。
type: docs
weight: 144
url: /zh/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() 方法

返回一个数组，其中包含指向 [DirectoryInfo](../) 对象的共享指针，这些对象表示当前对象所代表的目录中所有的子目录。

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) 方法

在当前对象所代表的目录中搜索满足指定搜索条件的目录。

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的目录的名称模式 |

### 返回值

返回一个数组，包含指向 [DirectoryInfo](../) 对象的共享指针，这些对象表示名称匹配 **searchPattern** 的找到的目录。

## DirectoryInfo::GetDirectories(const String\&, SearchOption) 方法

在当前对象所代表的目录或以该目录为根的整个目录树中搜索满足指定搜索条件的目录。

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的目录的名称模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜索是仅在当前对象所代表的目录中进行，还是在以当前对象所代表的目录为根的整个目录树中进行 |

### 返回值

返回一个数组，包含指向 [DirectoryInfo](../) 对象的共享指针，这些对象表示名称匹配 **searchPattern** 的找到的目录。

## 另请参阅

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)