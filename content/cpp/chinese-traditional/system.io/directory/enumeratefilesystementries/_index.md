---
title: EnumerateFileSystemEntries()
second_title: Aspose.Slides for C++ API 參考
description: 搜尋符合指定搜尋條件的檔案與目錄，搜尋範圍可在指定目錄內，或在以該目錄為根的整個目錄樹中。
type: docs
weight: 53
url: /zh-hant/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) 方法

搜尋符合指定搜尋條件的檔案與目錄，搜尋範圍可在指定目錄內，或在以該目錄為根的整個目錄樹中。

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要搜尋的目錄之完整或相對路徑 |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋的檔案與目錄的名稱模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜尋是僅在指定目錄內執行，還是於以該目錄為根的整個目錄樹中執行 |

### Return Value

可列舉的集合，包含符合 **searchPattern** 的已找到檔案與目錄的完整路徑

## See Also

* 列舉 [SearchOption](../../searchoption/)
* 型別別名 [StringEnumerablePtr](../stringenumerableptr/)
* 類別 [String](../../../system/string/)
* 類別 [Directory](../)
* 命名空間 [System::IO](../../)
* 程式庫 [Aspose.Slides](../../../)