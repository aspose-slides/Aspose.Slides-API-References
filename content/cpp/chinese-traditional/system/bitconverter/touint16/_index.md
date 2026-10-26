---
title: ToUInt16()
second_title: Aspose.Slides for C++ API 參考
description: 將指定陣列中從指定索引開始的兩個位元組轉換為 unsigned 16 位元整數值。
type: docs
weight: 92
url: /zh-hant/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) 方法


將指定陣列中從指定索引開始的兩個位元組轉換為 unsigned 16 位元整數值。

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中開始取位元組進行轉換的索引 |

### 回傳值

轉換後得到的 unsigned 16 位元整數值

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) 方法


將指定陣列中從指定索引開始的兩個位元組轉換為 unsigned 16 位元整數值。

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中開始取位元組進行轉換的索引 |

### 回傳值

轉換後得到的 unsigned 16 位元整數值

## 另請參閱

* 型別定義 [ArrayPtr](../../arrayptr/)
* 類別 [BitConverter](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)