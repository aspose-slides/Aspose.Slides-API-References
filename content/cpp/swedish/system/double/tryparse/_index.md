---
title: TryParse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande dubbelprecision flyttal.
type: docs
weight: 14
url: /sv/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande dubbelprecision flyttal.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| result | **double**\& | Referensen till en dubbelprecision flyttalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

Sant om konverteringen lyckades, annars - falskt.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) metod

Konverterar den angivna strängen som innehåller talets textrepresentation till motsvarande dubbelprecision flyttal med den angivna formateringsinformationen och talstilen.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enumerationen som specificerar den tillåtna stilen för talets textrepresentation. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formateringsinformationen. |
| result | **double**\& | Referensen till en dubbelprecision flyttalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

Sant om konverteringen lyckades, annars - falskt.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) metod

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) metod

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) metod

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)