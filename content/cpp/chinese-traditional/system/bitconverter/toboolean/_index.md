---
title: ToBoolean()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定陣列中從指定索引開始的單一位元組轉換為布林值。
type: docs
weight: 27
url: /zh-hant/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) method

將指定陣列中從指定索引開始的單一位元組轉換為布林值。

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中開始取位元組進行轉換的索引 |

### 傳回值

[Boolean](../../boolean/) 轉換後的值

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) method

將指定陣列中從指定索引開始的單一位元組轉換為布林值。

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | 包含要轉換的位元組的 ArrayView |
| startIndex | int | [Index](../../index/) 在陣列中開始取位元組進行轉換的索引 |

### 傳回值

[Boolean](../../boolean/) 轉換後的值

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* 類別 [BitConverter](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)