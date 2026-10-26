---
title: CheckPath()
second_title: Aspose.Slides for C++ API 參考
description: 判斷指定的路徑是否有效，方法是檢查其是否包含無效字元。如果路徑包含無效字元，將拋出例外。
type: docs
weight: 209
url: /zh-hant/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) 方法

判斷指定的路徑是否有效，方法是檢查其是否包含無效字元。如果路徑包含無效字元，將拋出例外。

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要檢查的路徑 |
| msg | const [String](../../../system/string/)\& | 傳遞給例外物件建構式的訊息 |
| allow_empty | **bool** | 指定是否應將空字串或 null 字串視為正確的路徑（true）或不視為正確的路徑（false）；如果此參數為 false 且 **path** 為空，將拋出 ArgumentException；如果此參數為 false 且 **path** 為 null，將拋出 ArgumentNullException |

## 參見

* 類別 [String](../../../system/string/)
* 類別 [Path](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)