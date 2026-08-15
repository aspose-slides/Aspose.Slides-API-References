---
title: ReadLines()
second_title: Aspose.Slides for C++ API 參考文件
description: 逐行讀取指定文字檔的內容，使用指定的字元編碼，並返回可列舉的字串集合，每個字串代表檔案內容中的單一行。
type: docs
weight: 326
url: /zh-hant/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) 方法

逐行讀取指定文字檔的內容，使用指定的字元編碼，並返回可列舉的字串集合，每個字串代表檔案內容中的單一行。

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要讀取的檔案路徑 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字元編碼 |

### 返回值

可列舉的字串集合，代表指定檔案的內容

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* 類別 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 類別 [String](../../../system/string/)
* 類別 [File](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)