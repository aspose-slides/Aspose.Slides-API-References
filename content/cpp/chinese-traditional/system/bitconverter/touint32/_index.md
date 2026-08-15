---
title: ToUInt32()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定陣列中自指定索引開始的四個位元組轉換為無號 32 位元整數值。
type: docs
weight: 105
url: /zh-hant/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) 方法

將指定陣列中自指定索引開始的四個位元組轉換為無號 32 位元整數值。

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 其中包含待轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中開始取位元組進行轉換的索引 |

### 返回值

轉換產生的無號 32 位元整數值

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) 方法

將指定陣列中自指定索引開始的四個位元組轉換為無號 32 位元整數值。

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 其中包含待轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中開始取位元組進行轉換的索引 |

### 返回值

轉換產生的無號 32 位元整數值

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* 類別 [BitConverter](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)