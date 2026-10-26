---
title: GetFileSystemEntries()
second_title: Aspose.Slides for C++ API 參考
description: 搜尋符合指定搜尋條件的檔案與目錄，可在指定的目錄中或在以該目錄為根的整個目錄樹中執行。
type: docs
weight: 92
url: /zh-hant/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String&, const String&, SearchOption) 方法

搜尋符合指定搜尋條件的檔案與目錄，可在指定的目錄中或在以該目錄為根的整個目錄樹中執行。

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要搜尋的目錄之完整或相對路徑 |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋之檔案與目錄的名稱模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜尋是僅在指定的目錄中執行，還是於以該目錄為根的整個目錄樹中執行 |

### 回傳值

回傳一個陣列，內容為符合 **searchPattern** 名稱的找到之檔案與目錄的完整路徑

## 另見

* 列舉 [SearchOption](../../searchoption/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [Directory](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)