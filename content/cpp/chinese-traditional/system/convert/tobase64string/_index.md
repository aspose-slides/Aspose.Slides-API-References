---
title: ToBase64String()
second_title: Aspose.Slides for C++ API 參考
description: Base-64 將指定位元組陣列中的元素編碼，並以字串形式返回編碼後的資料。
type: docs
weight: 40
url: /zh-hant/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) 方法


Base-64 會編碼指定位元組陣列中的元素，並將編碼後的資料以字串形式返回。

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 要編碼的位元組陣列 |
| insert_line_breaks | **bool** | 指定是否在輸出字串中每 76 個 base-64 字元後插入換行字元 |

### 回傳值

包含輸入陣列之 base-64 編碼表示的字串

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) 方法


Base-64 會編碼指定位元組陣列中一段範圍的元素，並將編碼後的資料以字串形式返回。

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 包含要編碼之元素範圍的位元組陣列 |
| offset_in | int | 輸入陣列中開始編碼之範圍的元素索引 |
| length | int | 要編碼之元素範圍的長度 |
| insert_line_breaks | **bool** | 指定是否在輸出字串中每 76 個 base-64 字元後插入換行字元 |

### 回傳值

包含輸入陣列中元素範圍之 base-64 編碼表示的字串

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) 方法


Base-64 會編碼指定位元組陣列中的元素，並將編碼後的資料以字串形式返回。

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 要編碼的位元組陣列 |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | 指定 base-64 編碼資料的格式化選項 |

### 回傳值

包含輸入陣列之 base-64 編碼表示的字串

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) 方法


Base-64 會編碼指定位元組陣列中一段範圍的元素，並將編碼後的資料以字串形式返回。

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 包含要編碼之元素範圍的位元組陣列 |
| offset_in | int | 輸入陣列中開始編碼之範圍的元素索引 |
| length | int | 要編碼之元素範圍的長度 |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | 指定 base-64 編碼資料的格式化選項 |

### 回傳值

包含輸入陣列中元素範圍之 base-64 編碼表示的字串

## 另請參閱

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)