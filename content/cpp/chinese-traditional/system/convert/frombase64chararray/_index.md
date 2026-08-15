---
title: FromBase64CharArray()
second_title: Aspose.Slides for C++ API 參考文件
description: 將以 Unicode 字元陣列中範圍表示的 Base-64 編碼資料解碼。
type: docs
weight: 53
url: /zh-hant/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) 方法


將表示為 Unicode 字元陣列中範圍的 Base-64 編碼資料解碼。

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 包含要解碼資料的陣列 |
| offset | int | 輸入陣列中解碼範圍開始的位置 |
| length | int | 要解碼的範圍長度 |

### 返回值

包含已解碼資料的位元組陣列

## 參見

* 類型別名 [ArrayPtr](../../arrayptr/)
* 結構 [Convert](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)