---
title: GetFiles()
second_title: Aspose.Slides for C++ API 參考
description: 返回一個陣列，其中包含指向 FileInfo 物件的共享指標，這些物件代表目前物件所表示目錄中所有的目錄。
type: docs
weight: 157
url: /zh-hant/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() 方法


返回一個陣列，其中包含指向 [FileInfo](../../fileinfo/) 物件的共享指標，這些物件代表目前物件所表示目錄中的所有目錄。

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) 方法


在目前物件所表示的目錄中搜尋符合指定搜尋條件的檔案。

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋的檔案名稱模式 |

### 返回值

返回一個陣列，其中包含指向 [FileInfo](../../fileinfo/) 物件的共享指標，這些物件代表名稱符合 **searchPattern** 的找到的檔案。

## DirectoryInfo::GetFiles(const String\&, SearchOption) 方法


在目前物件所表示的目錄或根植於該目錄的整個目錄樹中搜尋符合指定搜尋條件的檔案。

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋的檔案名稱模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜尋是否僅在目前物件所表示的目錄中執行，或在以該目錄為根的整個目錄樹中執行 |

### 返回值

返回一個陣列，其中包含指向 [FileInfo](../../fileinfo/) 物件的共享指標，這些物件代表名稱符合 **searchPattern** 的找到的檔案。

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)