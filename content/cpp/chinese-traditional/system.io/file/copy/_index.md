---
title: Copy()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的檔案複製到指定的位置。如果目標檔案已經存在，參數會指定是否應該覆寫。
type: docs
weight: 40
url: /zh-hant/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) 方法


將指定的檔案複製到指定的位置。如果目標檔案已經存在，參數會指定是否應該覆寫。

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | 要複製的檔案路徑 |
| destFileName | const [String](../../../system/string/)\& | 要複製的檔案的新位置路徑 |
| overwrite | **bool** | True 如果應該覆寫已存在的目標檔案，false 如果目標檔案已存在且不應覆寫，導致複製失敗 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [File](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)