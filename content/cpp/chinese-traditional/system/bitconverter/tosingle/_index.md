---
title: ToSingle()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定陣列中從指定索引開始的四個位元組轉換為單精度浮點值。
type: docs
weight: 131
url: /zh-hant/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) 方法

將指定陣列中從指定索引開始的四個位元組轉換為單精度浮點值。

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要轉換的位元組 |
| startIndex | int | 在陣列中 [Index](../../index/)，用於開始取位元組進行轉換 |

### 傳回值

由轉換產生的單精度浮點值

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) 方法

將指定陣列中從指定索引開始的四個位元組轉換為單精度浮點值。

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 包含要轉換的位元組 |
| startIndex | int | 在陣列中 [Index](../../index/)，用於開始取位元組進行轉換 |

### 傳回值

由轉換產生的單精度浮點值

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* 類別 [BitConverter](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)