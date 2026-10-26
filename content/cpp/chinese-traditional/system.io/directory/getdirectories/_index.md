---
title: GetDirectories()
second_title: Aspose.Slides for C++ API 參考
description: 搜尋符合指定搜尋條件的目錄，搜尋範圍可以是指定的目錄或是以該目錄為根的整個目錄樹。
type: docs
weight: 66
url: /zh-hant/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) 方法

搜尋符合指定搜尋條件的目錄，搜尋範圍可以是指定的目錄或是以該目錄為根的整個目錄樹。

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要搜尋的目錄的完整或相對路徑 |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋的目錄的名稱模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定搜尋是僅在指定目錄中執行，還是於以該目錄為根的整個目錄樹中執行 |

### 返回值

一個包含符合 **searchPattern** 名稱的已找到目錄的完整路徑的陣列

## 另請參閱

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [Directory](../)
* 命名空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)