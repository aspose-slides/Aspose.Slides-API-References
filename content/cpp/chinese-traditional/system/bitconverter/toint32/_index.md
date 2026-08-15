---
title: ToInt32()
second_title: Aspose.Slides for C++ API 參考
description: 將指定陣列中從指定索引開始的四個位元組轉換為 32 位元整數值。
type: docs
weight: 66
url: /zh-hant/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) method

將指定陣列中從指定索引開始的四個位元組轉換為 32 位元整數值。

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中開始取位元組進行轉換的索引 |

### 傳回值

32-bit integer value resulting from conversion

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) method

將指定陣列中從指定索引開始的四個位元組轉換為 32 位元整數值。

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中開始取位元組進行轉換的索引 |

### 傳回值

32-bit integer value resulting from conversion

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)