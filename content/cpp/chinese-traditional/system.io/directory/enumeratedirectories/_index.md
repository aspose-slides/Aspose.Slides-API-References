---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API 參考文件
description: 搜尋符合指定搜尋條件的目錄，可以在指定的目錄內或在根自該目錄的整個目錄樹中進行搜尋。
type: docs
weight: 27
url: /zh-hant/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) 方法

搜尋符合指定搜尋條件的目錄，可以在指定的目錄內或在根自該目錄的整個目錄樹中進行搜尋。

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要搜尋之目錄的完整或相對路徑 |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋的目錄名稱模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定是否僅在指定目錄內執行搜尋，或在根自該目錄的整個目錄樹中執行搜尋 |

### 返回值

符合 **searchPattern** 名稱的找到的目錄之完整路徑的可列舉集合

## 另見

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)