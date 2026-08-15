---
title: EnumerateFiles()
second_title: Aspose.Slides for C++ API 參考文件
description: 搜尋符合指定搜尋條件的檔案，可在指定目錄中或在以該目錄為根的整個目錄樹中進行搜尋。
type: docs
weight: 40
url: /zh-hant/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String&, const String&, SearchOption) 方法

搜尋符合指定搜尋條件的檔案，可在指定目錄內或在以該目錄為根的整個目錄樹中搜尋。

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 完整或相對路徑，指向要搜尋的目錄 |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋的檔案之名稱模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定是否僅在指定的目錄中執行搜尋，或在以該目錄為根的整個目錄樹中執行搜尋 |

### 回傳值

可列舉的集合，包含符合 **searchPattern** 的已找到檔案的完整路徑

## 另請參閱

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)