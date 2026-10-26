---
title: AppendAllLines()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定字串集合中的字串使用指定的編碼逐行寫入指定檔案。若指定的檔案不存在，將會建立它。寫入所有字串後，檔案會被關閉。
type: docs
weight: 1
url: /zh-hant/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) method

將指定字串集合中的字串使用指定的編碼逐行寫入指定檔案。若指定的檔案不存在，將會建立它。寫入所有字串後，檔案會被關閉。

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要追加字串的檔案路徑 |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | 要寫入檔案的字串 |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 要使用的字元編碼 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* 類別 [String](../../../system/string/)
* 類別 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 類別 [File](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)