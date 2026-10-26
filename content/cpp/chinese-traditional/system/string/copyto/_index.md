---
title: CopyTo()
second_title: Aspose.Slides for C++ API 參考文件
description: 將字串字元複製到現有的陣列元素中。此過程不會調整大小。
type: docs
weight: 430
url: /zh-hant/system/string/copyto/
---
## String::CopyTo(int, const ArrayPtr\<char_t\>\&, int, int) const 方法

將字串字元複製到現有的陣列元素中。此過程不會改變大小。

```cpp
void System::String::CopyTo(int sourceIndex, const ArrayPtr<char_t> &destination, int destinationIndex, int count) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceIndex | int | 字串內的索引，指示從何處開始讀取。 |
| destination | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 目標陣列。 |
| destinationIndex | int | 陣列內的索引，指示從何處開始寫入。 |
| count | int | 要複製的字元數量。 |

## 另見

* 型別別名 [ArrayPtr](../../arrayptr/)
* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)