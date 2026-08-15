---
title: ToInt64()
second_title: Aspose.Slides for C++ API 參考
description: 將指定陣列中從指定索引開始的八個位元組轉換為 64 位元整數值。
type: docs
weight: 79
url: /zh-hant/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) method

將指定陣列中從指定索引開始的八個位元組轉換為 64 位元整數值。

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 其中包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中，用於開始取位元組進行轉換的索引 |

### 返回值

轉換後得到的 64 位元整數值

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) method

將指定陣列中從指定索引開始的八個位元組轉換為 64 位元整數值。

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 其中包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中，用於開始取位元組進行轉換的索引 |

### 返回值

轉換後得到的 64 位元整數值

## 另請參閱

* 類型定義 [ArrayPtr](../../arrayptr/)
* 類別 [BitConverter](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)