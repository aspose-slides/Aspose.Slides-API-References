---
title: ToDouble()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定陣列中從指定索引開始的八個位元組轉換為雙精度浮點值。
type: docs
weight: 144
url: /zh-hant/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) 方法

將指定陣列中從指定索引開始的八個位元組轉換為雙精度浮點值。

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 表示陣列中開始取位元組進行轉換的索引 |

### 回傳值

轉換後的雙精度浮點值

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) 方法

將指定陣列中從指定索引開始的八個位元組轉換為雙精度浮點值。

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要轉換的位元組的 ArrayView |
| startIndex | int | [Index](../../index/) 表示陣列中開始取位元組進行轉換的索引 |

### 回傳值

轉換後的雙精度浮點值

## 參見

* Typedef [ArrayPtr](../../arrayptr/)
* 類別 [BitConverter](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)