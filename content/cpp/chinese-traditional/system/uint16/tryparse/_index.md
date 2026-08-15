---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的字串（其內容為數字的字串表示）轉換為等效的 16 位元無號整數。
type: docs
weight: 14
url: /zh-hant/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) method


將指定的 String（包含數字的字串表示）轉換為等效的 16 位元無號整數。

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| result | **uint16_t**\& | 用於放置轉換結果的 16 位元無號整數變數的參考。 |

### 回傳值

如果轉換成功則回傳 true，否則回傳 false。

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) method


使用提供的格式資訊和數字樣式，將指定的 String（包含數字的字串表示）轉換為等效的 16 位元無號整數。

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的位元組合，指定允許的字串表示樣式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字串格式資訊的物件指標。 |
| result | **uint16_t**\& | 用於放置轉換結果的 16 位元無號整數變數的參考。 |

### 回傳值

如果轉換成功則回傳 true，否則回傳 false。

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## 相關參考

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)