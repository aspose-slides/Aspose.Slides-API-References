---
title: ToString()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定位元組陣列的所有值轉換為其十六進位字串表示形式。十六進位表示法中使用的字母大小寫以及插入於相鄰位元組之間的分隔符號，皆透過相應的參數指定。
type: docs
weight: 157
url: /zh-hant/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) 方法

將指定位元組陣列的所有值轉換為其十六進位字串表示形式。十六進位表示法中使用的字母大小寫以及插入於相鄰位元組之間的分隔符號，皆透過相應的參數指定。

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要轉換的位元組 |
| uppercase | **bool** | 指定在最終十六進位表示中使用的字母大小寫 |
| separator | const [String](../../string/)\& | 在最終字串中，作為插入於相鄰位元組之間的分隔符號的字串 |

### 傳回值

[String](../../string/) 包含指定位元組陣列的十六進位表示

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) 方法

將指定位元組陣列的值自指定索引起轉換為十六進位字串表示。

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在指定陣列中開始轉換的索引 |

### 傳回值

[String](../../string/) 包含指定陣列中指定範圍元素的十六進位表示

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) 方法

將指定位元組陣列的一段值轉換為其十六進位字串表示形式。

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 包含要轉換的位元組 |
| startIndex | int | [Index](../../index/) 在指定陣列中開始轉換之位元組範圍的起始位置 |
| length | int | 要轉換的位元組範圍之長度 |

### 傳回值

[String](../../string/) 包含指定陣列中指定範圍元素的十六進位表示

## 參見

* 型別定義 [ArrayPtr](../../arrayptr/)
* 類別 [String](../../string/)
* 類別 [BitConverter](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)