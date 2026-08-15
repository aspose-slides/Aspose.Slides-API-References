---
title: ToBase64CharArray()
second_title: Aspose.Slides for C++ API 參考
description: Base-64 將指定位元組陣列中的一段元素編碼，並將編碼資料儲存為 Unicode 字元陣列。
type: docs
weight: 27
url: /zh-hant/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) method

Base-64 會對指定位元組陣列中的一段元素進行編碼，並將編碼資料儲存為 Unicode 字元陣列。

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 包含要編碼之元素區段的位元組陣列 |
| offset_in | int | 輸入陣列中元素的索引，指示編碼區段的起始位置 |
| length | int | 要編碼的元素區段之長度 |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | 指向要放置結果資料之輸出陣列的常量參考 |
| offset_out | int | 輸出陣列中放置結果資料的起始索引 |
| insert_line_breaks | **bool** | 指定是否在每 76 個 base-64 字元後於輸出陣列插入換行字元 |

### 傳回值

寫入輸出陣列的字元數量

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) method

Base-64 會對指定位元組陣列中的一段元素進行編碼，並將編碼資料儲存為 Unicode 字元陣列。

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 包含要編碼之元素區段的位元組陣列 |
| offset_in | int | 輸入陣列中元素的索引，指示編碼區段的起始位置 |
| length | int | 要編碼的元素區段之長度 |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 指向要放置結果資料之輸出陣列的常量參考 |
| offset_out | int | 輸出陣列中放置結果資料的起始索引 |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | 指定 base-64 編碼資料的格式化選項 |

### 傳回值

寫入輸出陣列的字元數量

## 另請參閱

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)