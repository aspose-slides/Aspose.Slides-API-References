---
title: ToByteArray()
second_title: Aspose.Slides for C++ API 參考
description: 將字串或子字串轉換為位元組陣列。
type: docs
weight: 508
url: /zh-hant/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const 方法

將字串或子字串轉換為位元組陣列。

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | **int32_t** | 子字串的起始索引。 |
| length | **int32_t** | 子字串的長度。 |
| LE | **bool** | 若為 true，則使用小端序編碼字元；否則使用大端序。 |

### 返回值

[Array](../../array/) 包含表示字串字符之位元組的。

## 另請參閱

* 類型定義 [ArrayPtr](../../arrayptr/)
* 類別 [String](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)