---
title: Parse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 16-bit osignerat heltal.
type: docs
weight: 1
url: /sv/system/uint16/parse/
---
## UInt16::Parse(const String\&) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 16-bit osignerat heltal.

```cpp
static uint16_t System::UInt16::Parse(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |

### Returvärde

Det 16-bit osignerade heltalet som är lika med talet som representeras av den angivna strängen.

## UInt16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 16-bit osignerat heltal med den angivna formateringsinformationen.

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller strängformatinformationen. |

### Returvärde

Det 16-bit osignerade heltalet som är lika med talet som representeras av den angivna strängen.

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, std::nullptr_t) metod 




```cpp
static uint16_t System::UInt16::Parse(const String &value, std::nullptr_t)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod

Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 16-bit osignerat heltal med den angivna formateringsinformationen och talstil.

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enum som specificerar den tillåtna stilen för talets teckenrepresentation. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller strängformatinformationen. |

### Returvärde

Det 16-bit osignerade heltalet som är lika med talet som representeras av den angivna strängen.

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod 




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod 




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metod 




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)