---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API 参考
description: 返回包含当前对象所表示目录中所有目录的可枚举集合。
type: docs
weight: 105
url: /zh/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() 方法

返回包含当前对象所表示目录中所有目录的可枚举集合。

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) 方法

在当前对象所表示的目录中搜索满足指定搜索条件的目录。

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的目录的名称模式 |

### 返回值

可枚举集合，包含指向 [DirectoryInfo](../) 对象的共享指针，这些对象表示名称匹配 **searchPattern** 的找到的目录。

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) 方法

在当前对象所表示的目录或以该目录为根的整个目录树中搜索满足指定搜索条件的目录。

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜索的目录的名称模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜索是仅在当前对象所表示的目录中进行，还是在以该目录为根的整个目录树中进行 |

### 返回值

可枚举集合，包含指向 [DirectoryInfo](../) 对象的共享指针，这些对象表示名称匹配 **searchPattern** 的找到的目录。

## 参见

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 类 [DirectoryInfo](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::IO](../../)
* Library [Aspose.Slides](../../../)