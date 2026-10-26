---
title: AppendAllText()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用指定的編碼將指定的字串追加到指定的檔案。
type: docs
weight: 14
url: /zh-hant/system.io/file/appendalltext/
---
## File::AppendAllText(const String\&, const String\&, const EncodingPtr\&) 方法

將指定的字串以指定的編碼追加至指定的檔案。

```cpp
static void System::IO::File::AppendAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要將字串追加至的檔案路徑 |
| contents | const [String](../../../system/string/)\& | 要寫入檔案的字串 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字元編碼 |

## 另見

* Typedef [EncodingPtr](../../../system/encodingptr/)
* 類別 [String](../../../system/string/)
* 類別 [File](../)
* 命名空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)