---
title: GetFileSystemInfos()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回一個陣列，其中包含指向 FileSystemInfo 物件的 shared pointers，這些物件代表位於當前物件所表示的目錄中的所有檔案和目錄。
type: docs
weight: 170
url: /zh-hant/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() 方法

返回一個陣列，其中包含指向 [FileSystemInfo](../../filesysteminfo/) 物件的 shared pointers，這些物件代表位於當前物件所表示的目錄中的所有檔案和目錄。

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) 方法

在當前物件所表示的目錄中，搜尋符合指定搜尋條件的檔案和目錄。

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋的檔案和目錄的名稱模式 |

### 回傳值

一個陣列，包含指向 [FileSystemInfo](../../filesysteminfo/) 物件的 shared pointers，這些物件代表名稱符合 **searchPattern** 的已找到檔案和目錄。

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) 方法


在當前物件所表示的目錄或該目錄為根的整個目錄樹中，搜尋符合指定搜尋條件的檔案和目錄。

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋的檔案和目錄的名稱模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜尋是僅在當前物件所表示的目錄中執行，還是於以該目錄為根的整個目錄樹中執行 |

### 回傳值

一個陣列，包含指向 [FileSystemInfo](../../filesysteminfo/) 物件的 shared pointers，這些物件代表名稱符合 **searchPattern** 的已找到檔案和目錄。

## 另見

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)