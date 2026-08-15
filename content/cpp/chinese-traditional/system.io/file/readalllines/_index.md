---
title: ReadAllLines()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的字元編碼，逐行將指定文字檔的內容讀取為字串陣列。
type: docs
weight: 300
url: /zh-hant/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) 方法


將指定文字檔的內容逐行讀取為字串陣列，並使用指定的字元編碼。

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要讀取的檔案路徑 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字元編碼 |

### 回傳值

字串陣列，每個元素代表指定檔案中的單一行

## 相關參考

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* 類別 [String](../../../system/string/)
* 類別 [File](../)
* 命名空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)