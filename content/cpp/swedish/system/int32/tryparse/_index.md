---
title: TryParse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen som innehåller en talrepresentation till motsvarande 32-bit signerade heltal.
type: docs
weight: 14
url: /sv/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) metod


Konverterar den angivna strängen som innehåller en talrepresentation till motsvarande 32-bit signerade heltal.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| result | **int32_t**\& | Referensen till en 32-bit signerad heltalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

True om konverteringen lyckades, annars - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) metod


Konverterar den angivna strängen som innehåller en talrepresentation till motsvarande 32-bit signerade heltal med den angivna formateringsinformationen och talstilen.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i enum-typen NumberStyles som specificerar den tillåtna stilen för talrepresentationen. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller information om strängformatet. |
| result | **int32_t**\& | Referensen till en 32-bit signerad heltalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

True om konverteringen lyckades, annars - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) metod




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) metod




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) metod




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [Int32](../)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)