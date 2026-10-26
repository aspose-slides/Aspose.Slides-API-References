---
title: Replace()
second_title: Aspose.Slides for C++ API 參考文件
description: 將一個檔案的內容取代為另一個檔案，並為被取代的檔案建立備份。
type: docs
weight: 339
url: /zh-hant/system.io/file/replace/
---
## File::Replace(const String&, const String&, const String&, bool) 方法

將一個檔案的內容取代為另一個檔案，並為被取代的檔案建立備份。

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | 用於取代的檔案名稱 |
| destinationFileName | const [String](../../../system/string/)\& | 被取代的檔案名稱 |
| destinationBackupFileName | const [String](../../../system/string/)\& | 備份檔案的名稱 |
| ignoreMetadataErrors | **bool** | 指定是否應忽略從被取代檔案合併至取代檔案的錯誤（true）或不忽略（false） |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [File](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)