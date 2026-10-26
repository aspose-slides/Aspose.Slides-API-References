---
title: OpenText()
second_title: Aspose.Slides C++ API 參考
description: 以不共享的方式使用 UTF-8 編碼打開指定的現有檔案以讀取文字。
type: docs
weight: 261
url: /zh-hant/system.io/file/opentext/
---
## File::OpenText(const String&, const EncodingPtr&) 方法

以不共享的方式使用 UTF-8 編碼打開指定的現有檔案以讀取文字。

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要開啟的檔案路徑 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字元編碼 |

### 返回值

指向與已開啟檔案相關聯的 [StreamWriter](../../streamwriter/) 物件的共享指標

## 另見

* Typedef [StreamReaderPtr](../../../system/streamreaderptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* 類別 [String](../../../system/string/)
* 類別 [File](../)
* 命名空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)