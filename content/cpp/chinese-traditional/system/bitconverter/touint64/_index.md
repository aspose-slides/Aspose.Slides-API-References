---
title: ToUInt64()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定陣列中自指定索引開始的八個位元組轉換為無符號 64 位元整數值。
type: docs
weight: 118
url: /zh-hant/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) 方法


將指定陣列中自指定索引開始的八個位元組轉換為無符號 64 位元整數值。

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中開始提取位元組以進行轉換的位置 |

### 返回值

轉換產生的無符號 64 位元整數值

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) 方法


將指定陣列中自指定索引開始的八個位元組轉換為無符號 64 位元整數值。

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中開始提取位元組以進行轉換的位置 |

### 返回值

轉換產生的無符號 64 位元整數值

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* 類別 [BitConverter](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)