---
title: TryParse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 8-bit unsigned heltal.
type: docs
weight: 14
url: /sv/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 8-bit unsigned heltal.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| result | **uint8_t**\& | Referensen till en 8-bit unsigned heltalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

true om konverteringen lyckades, annars - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 8-bit unsigned heltal med hjälp av den angivna formateringsinformationen och talstilen.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enumerationen som specificerar den tillåtna stilen för strängrepresentationen av ett tal. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller strängformatinformationen. |
| result | **uint8_t**\& | Referensen till en 8-bit unsigned heltalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

true om konverteringen lyckades, annars - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) metod

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) metod

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) metod

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [Byte](../)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)