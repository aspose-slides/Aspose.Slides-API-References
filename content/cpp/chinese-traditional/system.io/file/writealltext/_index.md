---
title: WriteAllText()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的文字檔或覆寫既有檔案，並使用指定的編碼將指定字串的內容寫入其中。
type: docs
weight: 469
url: /zh-hant/system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) 方法

建立新的文字檔或覆寫已有的檔案，並使用指定的編碼將指定字串的內容寫入其中。

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要建立或覆寫的檔案 |
| contents | const [String](../../../system/string/)\& | 字串陣列 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字元編碼 |

## 另請參閱

* Typedef [EncodingPtr](../../../system/encodingptr/)
* 類別 [String](../../../system/string/)
* 類別 [File](../)
* 命名空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)