---
title: GetChars()
second_title: Aspose.Slides for C++ API 參考
description: 取得從位元組緩衝區解碼得到的字元。
type: docs
weight: 92
url: /zh-hant/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) 方法


取得從位元組緩衝區解碼得到的字元。

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 以讀取位元組。 |
| byte_index | int | 輸入緩衝區位移。 |
| byte_count | int | 輸入緩衝區大小。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) 以放置字元。 |
| char_index | int | 輸出緩衝區位移。 |

### 傳回值

已寫入的字元數。

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) 方法


取得從位元組緩衝區解碼得到的字元。

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) 以讀取位元組。 |
| byte_count | int | 輸入緩衝區大小。 |
| chars | char_t * | [Buffer](../../../system/buffer/) 以放置字元。 |
| char_count | int | 輸出緩衝區大小。 |

### 傳回值

已寫入的字元數。

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) 方法


取得從位元組緩衝區解碼得到的字元。

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 以讀取位元組。 |
| byte_index | int | 輸入緩衝區位移。 |
| byte_count | int | 輸入緩衝區大小。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) 以放置字元。 |
| char_index | int | 輸出緩衝區位移。 |

### 傳回值

已寫入的字元數。

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) 方法


取得從位元組緩衝區解碼得到的字元。

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 以讀取位元組。 |
| index | int | 輸入緩衝區位移。 |
| count | int | 輸入緩衝區大小。 |

### 傳回值

[Buffer](../../../system/buffer/) 已解碼的字元數。

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) 方法


取得從位元組緩衝區解碼得到的字元。

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 以讀取位元組。 |

### 傳回值

[Buffer](../../../system/buffer/) 已解碼的字元數。

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) 方法


取得從位元組緩衝區解碼得到的字元。

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) 以讀取位元組。 |
| byte_count | int | 輸入緩衝區大小。 |
| chars | char_t * | [Buffer](../../../system/buffer/) 以放置字元。 |
| char_count | int | 輸出緩衝區大小。 |

### 傳回值

已寫入的字元數。

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [UTF7Encoding](../)
* 命名空間 [System::Text](../../)
* 程式庫 [Aspose.Slides](../../../)