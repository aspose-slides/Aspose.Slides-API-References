---
title: TryParse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 8-bitars signerat heltal.
type: docs
weight: 14
url: /sv/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) method

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 8-bits signerat heltal.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| result | **int8_t**\& | Referensen till en 8-bits signerat heltalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

True if the conversion succeeded, otherwise - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) method

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 8-bits signerat heltal med hjälp av den angivna formateringsinformationen och talstilen.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enum som specificerar den tillåtna stilen för talets teckenrepresentation. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formateringsinformationen för strängen. |
| result | **int8_t**\& | Referensen till en 8-bits signerat heltalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

True if the conversion succeeded, otherwise - false.

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

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)