---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回一個可列舉的集合，包含當前物件所表示的目錄中所有目錄。
type: docs
weight: 105
url: /zh-hant/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() 方法

返回一個可列舉的集合，包含當前物件所表示的目錄中所有目錄。

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) 方法

搜尋在當前物件所表示的目錄中符合指定搜尋條件的目錄。

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋的目錄名稱模式 |

### 返回值

可列舉的集合，包含指向 [DirectoryInfo](../) 物件的共享指標，這些物件代表名稱符合 **searchPattern** 的找到的目錄

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) 方法

搜尋在當前物件所表示的目錄或在以該目錄為根的整個目錄樹中符合指定搜尋條件的目錄。

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋的目錄名稱模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜尋是僅在當前物件所表示的目錄中執行，還是於以該目錄為根的整個目錄樹中執行 |

### 返回值

可列舉的集合，包含指向 [DirectoryInfo](../) 物件的共享指標，這些物件代表名稱符合 **searchPattern** 的找到的目錄

## 另請參閱

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)