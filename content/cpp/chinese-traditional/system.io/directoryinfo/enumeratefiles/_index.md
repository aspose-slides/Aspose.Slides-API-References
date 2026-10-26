---
title: EnumerateFiles()
second_title: Aspose.Slides for C++ API 參考
description: 返回一個可列舉的集合，包含目前物件所代表的目錄中所有檔案。
type: docs
weight: 118
url: /zh-hant/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() 方法

傳回可列舉的集合，其中包含目前物件所代表目錄中所有的檔案。

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) 方法

在目前物件所代表的目錄中搜尋符合指定搜尋條件的檔案。

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋之檔案的名稱模式 |

### 傳回值

可列舉的集合，包含指向 [FileInfo](../../fileinfo/) 物件的 shared pointers，這些物件代表名稱符合 **searchPattern** 的已找到檔案。

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) 方法

在目前物件所代表的目錄或根於該目錄的整個目錄樹中，搜尋符合指定搜尋條件的檔案。

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋之檔案的名稱模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜尋是僅在目前物件所代表的目錄中執行，還是於根於該目錄的整個目錄樹中執行 |

### 傳回值

可列舉的集合，包含指向 [FileInfo](../../fileinfo/) 物件的 shared pointers，這些物件代表名稱符合 **searchPattern** 的已找到檔案。

## 另請參閱

* 列舉 [SearchOption](../../searchoption/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [FileInfoPtr](../../../system/fileinfoptr/)
* 類別 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 類別 [DirectoryInfo](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)