---
title: AppendText()
second_title: Aspose.Slides for C++ API 參考手冊
description: 建立一個 StreamWriter 物件，以 UTF-8 編碼將文字附加到指定的檔案。若指定的檔案不存在，則會建立它。
type: docs
weight: 27
url: /zh-hant/system.io/file/appendtext/
---
## File::AppendText(const String\&) 方法

建立一個 [StreamWriter](../../streamwriter/) 物件，將文字以 UTF-8 編碼附加到指定的檔案。若指定的檔案不存在，則會建立它。

```cpp
static StreamWriterPtr System::IO::File::AppendText(const String &path)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要開啟或建立之檔案的路徑 |

### 返回值

指向已建立的 [StreamWriter](../../streamwriter/) 物件（與指定檔案相關聯）的共用指標

## 另請參閱

* 型別別名 [StreamWriterPtr](../../../system/streamwriterptr/)
* 類別 [String](../../../system/string/)
* 類別 [File](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)