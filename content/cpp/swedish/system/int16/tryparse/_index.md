---
title: TryParse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 16-bitars signerade heltal.
type: docs
weight: 14
url: /sv/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) metod


Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 16-bitars heltal med tecken.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| result | **int16_t**\& | Referensen till en 16-bitars heltalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

Sant om konverteringen lyckades, annars - falskt.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) metod


Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande 16-bitars heltal med tecken med hjälp av den angivna formateringsinformationen och talstil.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i enum-typen NumberStyles som specificerar den tillåtna stilen för talets teckenrepresentation. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formateringsinformationen för strängen. |
| result | **int16_t**\& | Referensen till en 16-bitars heltalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

Sant om konverteringen lyckades, annars - falskt.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) metod




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) metod




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) metod




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [Int16](../)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)