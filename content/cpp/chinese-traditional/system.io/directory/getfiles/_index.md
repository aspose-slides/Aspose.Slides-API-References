---
title: GetFiles()
second_title: Aspose.Slides for C++ API 參考
description: 搜尋符合指定搜尋條件的檔案，搜尋範圍可以是指定的目錄，或是以該目錄為根的整個目錄樹。
type: docs
weight: 79
url: /zh-hant/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) 方法

搜尋符合指定搜尋條件的檔案，搜尋範圍可以是指定的目錄，或是以該目錄為根的整個目錄樹。

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要搜尋的目錄的完整或相對路徑 |
| searchPattern | const [String](../../../system/string/)\& | 要搜尋的檔案名稱模式 |
| searchOption | [SearchOption](../../searchoption/) | 指定是否僅在指定的目錄中執行搜尋，或在以該目錄為根的整個目錄樹中執行搜尋 |

### 傳回值

一個陣列，包含符合 **searchPattern** 的已找到檔案的完整路徑

## 另請參閱

* 列舉 [SearchOption](../../searchoption/)
* 類型定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [String](../../../system/string/)
* 類別 [Directory](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)