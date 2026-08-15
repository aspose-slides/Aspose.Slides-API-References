---
title: ToInt16()
second_title: Aspose.Slides for C++ API 參考
description: 將指定陣列中從指定索引開始的兩個位元組轉換為 16 位元整數值。
type: docs
weight: 53
url: /zh-hant/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) 方法


將指定陣列中從指定索引開始的兩個位元組轉換為 16 位元整數值。

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中，用於開始取得位元組進行轉換 |

### 回傳值

16-bit integer value resulting from conversion

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) 方法


將指定陣列中從指定索引開始的兩個位元組轉換為 16 位元整數值。

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中，用於開始取得位元組進行轉換 |

### 回傳值

16-bit integer value resulting from conversion

## 另見

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)