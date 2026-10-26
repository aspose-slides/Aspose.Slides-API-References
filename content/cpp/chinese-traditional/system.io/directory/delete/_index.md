---
title: Delete()
second_title: Aspose.Slides for C++ API 參考
description: 移除指定的檔案或目錄。此操作不會拋出例外。
type: docs
weight: 14
url: /zh-hant/system.io/directory/delete/
---
## Directory::Delete(const String\&, bool) 方法


移除指定的檔案或目錄。此操作不會拋出例外。

```cpp
static void System::IO::Directory::Delete(const String &path, bool recursive=false)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要移除的目錄或檔案的路徑 |
| recursive | **bool** | 如果 **path** 指定一個非空目錄，則 **recursive** 指定是否應遞迴移除目錄的所有內容；如果 **path** 指定的目錄不是空的且 **recursive** 為 'false'，則操作失敗 |

## 參見

* 類別 [String](../../../system/string/)
* 類別 [Directory](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)