---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的字串（其內容為數字的字串表示形式）轉換為相等的 16 位元帶符號整數。
type: docs
weight: 14
url: /zh-hant/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) 方法

將指定的字串（其內容為數字的字串表示形式）轉換為相等的 16 位元帶符號整數。

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| result | **int16_t**\& | 指向 16 位元帶符號整數變數的參考，用於存放轉換結果。 |

### 返回值

若轉換成功則返回 true，否則返回 false。

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) 方法

使用提供的格式資訊和數字樣式，將指定的字串（其內容為數字的字串表示形式）轉換為相等的 16 位元帶符號整數。

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的位元組合，用於指定數字字串表示形式允許的樣式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊的物件的指標。 |
| result | **int16_t**\& | 指向 16 位元帶符號整數變數的參考，用於存放轉換結果。 |

### 返回值

若轉換成功則返回 true，否則返回 false。

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) 方法

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) 方法

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) 方法

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## 另見

* 列舉 [NumberStyles](../../../system.globalization/numberstyles/)
* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [Int16](../)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)