---
title: ToChar()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定陣列中從指定索引開始的兩個位元組轉換為 char_t 值。
type: docs
weight: 40
url: /zh-hant/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) 方法

將指定陣列中從指定索引開始的兩個位元組轉換為 char_t 值。

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中開始取得用於轉換的位元組的索引 |

### 返回值

轉換後產生的 char_t 值

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) 方法

將指定陣列中從指定索引開始的兩個位元組轉換為 char_t 值。

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在陣列中開始取得用於轉換的位元組的索引 |

### 返回值

轉換後產生的 char_t 值

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* 類別 [BitConverter](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)