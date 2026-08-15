---
title: ReadAllText()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的字元編碼，將指定文字檔的內容讀取為單一 String 物件。
type: docs
weight: 313
url: /zh-hant/system.io/file/readalltext/
---
## File::ReadAllText(const String\&, const EncodingPtr\&) 方法


讀取指定文字檔的內容，使用指定的字元編碼，將其放入單一 [String](../../../system/string/) 物件。

```cpp
static String System::IO::File::ReadAllText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要讀取的檔案路徑 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字元編碼 |

### 返回值

包含指定檔案內容的字串

## 另見

* Typedef [EncodingPtr](../../../system/encodingptr/)
* 類別 [String](../../../system/string/)
* 類別 [File](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)