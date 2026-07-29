---
title: TryParse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 32-bitars osignerade heltal.
type: docs
weight: 14
url: /sv/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 32-bitars osignerade heltal.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| result | **uint32_t**\& | Referensen till en 32-bitars osignerad heltalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

True om konverteringen lyckades, annars - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande 32-bitars osignerade heltal med hjälp av den angivna formateringsinformationen och talstilen.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enum som anger den tillåtna stilen för talets textrepresentation. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formateringsinformationen för strängen. |
| result | **uint32_t**\& | Referensen till en 32-bitars osignerad heltalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

True om konverteringen lyckades, annars - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) metod




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) metod




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) metod




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktur [UInt32](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)