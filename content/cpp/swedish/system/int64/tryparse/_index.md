---
title: TryParse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen som innehåller en siffra i textform till motsvarande 64-bitars signerade heltal.
type: docs
weight: 14
url: /sv/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) metod


Konverterar den angivna strängen som innehåller en siffra i textform till motsvarande 64-bitars signerade heltal.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| result | **int64_t**\& | Referensen till en 64-bitars signerad heltalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

True om konverteringen lyckades, annars - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) metod


Konverterar den angivna strängen som innehåller en siffra i textform till motsvarande 64-bitars signerade heltal med den angivna formateringsinformationen och talstilen.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enum som specificerar den tillåtna stilen för strängrepresentationen av ett tal. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller information om strängformatet. |
| result | **int64_t**\& | Referensen till en 64-bitars signerad heltalsvariabel där resultatet av konverteringen placeras. |

### Returvärde

True om konverteringen lyckades, annars - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) metod




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) metod




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) metod




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Se också

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* klass [String](../../string/)
* klass [Int64](../)
* klass [IFormatProvider](../../iformatprovider/)
* klass [CultureInfo](../../../system.globalization/cultureinfo/)
* klass [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* namnrymd [System](../../)
* Library [Aspose.Slides](../../../)