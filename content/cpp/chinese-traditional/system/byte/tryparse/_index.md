---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 將包含數字字串表示的指定字串轉換為等效的 8 位元無號整數。
type: docs
weight: 14
url: /zh-hant/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) method


將包含數字字串表示的指定字串轉換為等效的 8 位元無號整數。

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| result | **uint8_t**\& | 指向 8 位元無號整數變數的參考，轉換結果會放入該變數。 |

### 返回值

True if the conversion succeeded, otherwise - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) method


使用提供的格式資訊和數字樣式，將包含數字字串表示的指定字串轉換為等效的 8 位元無號整數。

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 指定允許的數字字串表示樣式的 NumberStyles 列舉值之位元組合。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字串格式資訊的物件指標。 |
| result | **uint8_t**\& | 指向 8 位元無號整數變數的參考，轉換結果會放入該變數。 |

### 返回值

True if the conversion succeeded, otherwise - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) method




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## 另請參閱

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)