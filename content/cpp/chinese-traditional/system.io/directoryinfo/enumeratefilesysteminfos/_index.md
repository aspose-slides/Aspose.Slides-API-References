---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides for C++ API 參考
description: 傳回包含當前物件所代表目錄中所有檔案和目錄的可列舉集合。
type: docs
weight: 131
url: /zh-hant/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() 方法


傳回包含當前物件所代表目錄中所有檔案和目錄的可列舉集合。

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) 方法


在當前物件所代表的目錄中搜尋符合指定搜尋條件的檔案和目錄。

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋的檔案和目錄的名稱模式 |

### 返回值

可列舉的集合，包含指向表示名稱符合 **searchPattern** 的已找到檔案和目錄之 [FileSystemInfo](../../filesysteminfo/) 物件的共享指標

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) 方法


在當前物件所代表的目錄或其根目錄下的整個目錄樹中搜尋符合指定搜尋條件的檔案和目錄。

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋的檔案和目錄的名稱模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定是否僅在當前物件所代表的目錄中執行搜尋，或在以該目錄為根的整個目錄樹中執行搜尋 |

### 返回值

可列舉的集合，包含指向表示名稱符合 **searchPattern** 的已找到檔案和目錄之 [FileSystemInfo](../../filesysteminfo/) 物件的共享指標

## 另請參閱

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)