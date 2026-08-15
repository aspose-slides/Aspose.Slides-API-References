---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 將包含數字字串表示的指定字串轉換為等效的 8 位元有號整數。
type: docs
weight: 14
url: /zh-hant/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) method

將包含數字字串表示的指定字串轉換為等效的 8 位元有號整數。

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| result | **int8_t**\& | 轉換結果寫入的 8 位元有號整數變數的參照。 |

### 回傳值

若轉換成功則回傳 true，否則回傳 false。

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) method

使用提供的格式資訊和數字樣式，將包含數字字串表示的指定字串轉換為等效的 8 位元有號整數。

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 指定允許的數字字串表示樣式的 NumberStyles 列舉的位元組合。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字串格式資訊的物件指標。 |
| result | **int8_t**\& | 轉換結果寫入的 8 位元有號整數變數的參照。 |

### 回傳值

若轉換成功則回傳 true，否則回傳 false。

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) method




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) method




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) method




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## 參見

* 列舉 [NumberStyles](../../../system.globalization/numberstyles/)
* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 結構 [SByte](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)