---
title: GetChars()
second_title: Aspose.Slides for C++ API 參考
description: 取得從位元組緩衝區解碼而得到的字元。
type: docs
weight: 274
url: /zh-hant/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) 方法


取得從位元組緩衝區解碼而得到的字元。

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於讀取位元組。 |
| byte_index | int | Input buffer offset. |
| byte_count | int | Input buffer size. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) 用於放置字元。 |
| char_index | int | Output buffer offset. |

### 傳回值

Number of written characters.

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) 方法


取得從位元組緩衝區解碼而得到的字元。

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於讀取位元組。 |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### 傳回值

[Buffer](../../../system/buffer/) 已解碼字元。

## Encoding::GetChars(ArrayPtr\<uint8_t\>) 方法


取得從位元組緩衝區解碼而得到的字元。

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於讀取位元組。 |

### 傳回值

[Buffer](../../../system/buffer/) 已解碼字元。

## Encoding::GetChars(const uint8_t *, int, char_t *, int) 方法


取得從位元組緩衝區解碼而得到的字元。

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) 用於讀取位元組。 |
| byte_count | int | Input buffer size. |
| chars | char_t * | [Buffer](../../../system/buffer/) 用於放置字元。 |
| char_count | int | Output buffer size. |

### 傳回值

Number of written characters.

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)